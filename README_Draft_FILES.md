# Draft of files available on Jasmin


CO9 is not quite finished yet but I can start to populate some sample files jasmin to get people started.

In time when Co9 is fully defined I pair this back to include only the definitive files that describe Co9k.

Some users will just want what is needed to run CO7 but in 404 (or P0.0 in the sensitivity trials) so we can include that too

The space on jasmin was populate back in 2020 to confuse issues further and will need a clean out.

Files are going to be publicly available:

https://gws-access.jasmin.ac.uk/public/jmmp_collab/AMM15/


Note the experimental merves of EMODNET/GEBCO are available under:

https://gws-access.jasmin.ac.uk/public/jmmp_collab/AMM15/GATHER_EXPERIMENTAL_EMODNET_GEBCO_DOMAIN_CFG/

of which https://gws-access.jasmin.ac.uk/public/jmmp_collab/AMM15/GATHER_EXPERIMENTAL_EMODNET_GEBCO_DOMAIN_CFG/PRODUCE_CFG_FILE_MERGE_GEBCO_DEEP_TO_200-100_EMODNET_TO_10-5_GEBCO_TO_COAST_domain_cfg.nc 
is the most relevant.

However we have increments further on that too.

The underlying bathy for the above domain cfgs are under:

https://gws-access.jasmin.ac.uk/public/jmmp_collab/AMM15/GATHER_EXPERIMENTAL_EMODNET_GEBCO_DOMAIN_CFG/INPUT_BATHY/


The most recent files that deal with WAD issues with rivers etc are here:

https://gws-access.jasmin.ac.uk/public/jmmp_collab/AMM15/AMM15_BATHY/

and will probably constitute something very close to the final AMMy bathy,Config file


Under FORCING, we have 
 * BDY/
    * BALTIC/
      * Set od bdys for baltic 2004 as used in P.x ensemble Uses v interp on the fly)
    * EXPER_NO_VERT_BDY_SJPZ_A_AND_D/
      * This is 3D TS on GLOSEA vertical grid. It allows for interpolaton in the vertical  on the fly. Useful when changing the target vertical level.
      At some point need UV version in the same format, currently just have 3D UV but pre interpolated to CO7 v grid.
    * SJPZ_A_AND_D_BT/
      * Barotropic bdys files
    * amm15_Baltic
      * baltic files in yearly format
    * amm15_sjpza_RMAX.1_RIM15/ 
     * TS files on CO7 vertical grid
 * DOMAIN_CFG/ (move this up a dir level)
 * RESTART/
   * Initial files used for non WAD runs with CO7 bathy and grid. Need equivalent for latest bathy and ME coordinates here
 * RIVERS/
 * SBC/
    * ERAI
    * OLD set of broken links to ERA5 need to removes this
 * TIDES/
   * FES2014/
   * TOPX/