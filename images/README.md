# images/

The template's `\includefig` macro loads figures from this folder. The methodology chapter
expects the files below. Each one currently shows a framed placeholder
(`\placeholderfig{...}`). Once you have added the image, replace the placeholder with
`\includefig{<width>}{<file>}{<caption>}{<label>}`, keeping the same width, caption and label.

| Label | File | Content |
|---|---|---|
| fig:setup | ln_setup_photo.png | Photo of the CO3620-2G and CO3620-2A lab setup |
| fig:fbd | cart_pendulum_fbd.png | Free-body diagram of the cart and pendulum (your own drawing) |
| fig:a62 | a62_control_routine.png | Screenshot of the Control-Routine subsystem |
| fig:candidates | mpc_candidates_step.png | Candidate step-response plot from Calculations.m |
| fig:sscontroller | state_space_controller_mpc.png | Screenshot of the State Space Controller subsystem with the MPC block |
| fig:plantsim | a62_mpc_sim_plant.png | Screenshot of the "CO3620-2G Plant" subsystem in A62_MPC_Sim |
