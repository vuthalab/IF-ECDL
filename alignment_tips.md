## Tips for aligning the laser 

1. Put the diode in the collimation tube and mount it to a free laser diode mount outside of the laser box. Connect the laser to the current controller and shine it onto a wall far away and then proceed to collimate using the lens in the tube.

2. Once the diode is collimated, place the tube back into the actual mount in the laser box and rotate it until it is in the desired oreintation. If this is a new laser, just choice whatever you oreintation you want (being cognisant of polarization for the PBS). If you are replacing a diode, try to rotate the tube until the alignment looks like it is best matched with the existing anamorphic prisms.

3. Ensuring that you have ~20-30% of your power is directed to the feedback path, set up a path for the output of the laser so that it is fiber coupled into the wavemeter but ignore the actual reading until much later. In addition, setup a power meter to read the output of the diode, ideally before the isolator.

4. Turn your laser current up to around the typical current (or enough that it is clearly visible) and setup your mirror and retroreflector. By eye, align the incoming beam from the mirror to the outgoing beam to the retroflector so that they overlap well. Once they are aligned enough by eye, check with the powermeter to see if you have feedback. You can do this by blocking the light in the feedback path -- if the output power decreases, then you have some feedback going to the diode.

5. With the coarse alignment done, tune your diode back down to around threshold (go with what you physically measure as threshold, not what the datasheet says). This corresponds to around 50 – 200 uW seen on the powermeter. Now do a fine alignment of the feedback path using both knobs on the mirrors and the cateye. More feedback should result in more power seen on the powermeter. As a metric, your feedback is well aligned when see 3 – 5 times more power compared to blocking the feedback path. This actually number may vary from diode to diode, and it depends on how close you are to threshold, but the point is that you should see increased lazing that is attributed to the feedback.
   
6. With the feedback well aligned, turn your diode current up to the desired amount, which should be within 15% of the maximum current (the closer the better, with some room of course). Operating at this higher current will add more power to your feedback path (and more power to the actual output) which will make your laser more stable. Now add the interference filter into the feedback path and look at the output of the wavemeter. Tune the angles of the interference filter to get within 100 GHz of your desired frequency. This part can be tricky but just keep trying different angles and follow the values that the wavemeter is trending to get there. If you are not getting close at all, then try changing the diode temperature in the correct direction.

7. Once you are near the desired frequency, just use small combinations of changing current, temperature, and IF angle to reach your desired frequency.

If you are trying to improve your laser stability, consider decreasing the size of the feedback path as this should also help.
