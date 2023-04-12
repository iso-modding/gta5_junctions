

		Ideally to have working, bb-min/max sets the area as junction and turns on the streetlights and behave same way as any other working juction, right now seems like most lights are set to 10 seconds

/!\ File junctions_file_with_modifications.zip is where the file with the extra/custom junction is
Files junctions.pso and xml found on "resource_junctions" are vanilla
After exporting the PSO to XML using RPF Explorer, and adding a custom junction, then re-importing, fails, RPF Explorer throws an error, Dexy confirmed, so the XML path on gta5.meta is the only change I made   

GTA5.meta - Replaced line 1098  

From
<filename>common:/data/levels/gta5/junctions.xml</filename>

To
<filename>resources:/resource_junctions/junctions.xml</filename>
========================================================================================
Junction file, xml and gta5.meta were taken from "GTA5\Grand Theft Auto V\update\update.rpf\common\data\levels\gta5\"
========================================================================================
BB-min/max: 	-1225.42, -2238.72, 39.16 
		-1218.35, -2304.1, 13.26
========================================================================================
Junction center (guessed from CW's camera position):

		-1224.79, -2272.64, 15.01
========================================================================================
XML got a junction defined this way:

      <vJunctionMin x="150.250000" y="-842.250000" z="28.156250" />
      <vJunctionMax x="197.000000" y="-796.250000" z="38.156250" />
========================================================================================
XML got a junction's center this way:

      <vJunctionNodePositions content="vector3_array">
        172.500000  -818.250000 30.156250   
========================================================================================
XML sets numer of lights this way:

      <iNumTrafficLightLocations value="4" />
========================================================================================
XML sets a lights position/node this way:

          <vNodePosition x="150.250000" y="-810.000000" z="30.156250" />
========================================================================================
I included an YMAP and added 8 street lights, location:

	-1222.35, -2288.28, 36.96


