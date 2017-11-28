# The mesoscale Hydrological Model -- mHM

- The current release is **[mHM v5.7][2]** ([Download as zip][3]).
- Please read the [user manual][4].
- The mHM comes with a [LICENSE][1] agreement, this includes also the GNU Lesser General Public License.
- A summary of the mHM history, i.e. implemented features, the list of resolved bugs and the specification of known bugs can be found in the file [RELEASES][5] or in the [release notes online][6].

## Cite as

Please refer to the main model developments by citing Samaniego et al. (2010) and Kumar et al. (2013):

- Samaniego L., R. Kumar, S. Attinger (2010): [Multiscale parameter regionalization of a grid-based hydrologic model at the mesoscale](http://onlinelibrary.wiley.com/doi/10.1029/2008WR007327/abstract). Water Resour. Res., 46,W05523, doi:10.1029/2008WR007327.
- Kumar, R., L. Samaniego, and S. Attinger (2013): [Implications of distributed hydrologic model parameterization on water fluxes at multiple scales and locations](http://onlinelibrary.wiley.com/doi/10.1029/2012WR012195/abstract), Water Resour. Res., 49, doi:10.1029/2012WR012195. 

## Quick start

1. compile mHM with the `make` command using settings from [Makefile](Makefile)
2. run mHM on a test basin with the command `./mhm` using settings from the [mhm.nml](mhm.nml)
3. explore the results in the [output directory](test_basin/) using a NetCDF viewer (e.g., `ncview`)


[1]: LICENSE
[2]: https://git.ufz.de/mhm/mhm/tags/v5.7
[3]: https://git.ufz.de/mhm/mhm/repository/v5.7/archive.zip
[4]: mhm_manual_v5.7.pdf
[5]: RELEASES
[6]: https://git.ufz.de/mhm/mhm/tags/