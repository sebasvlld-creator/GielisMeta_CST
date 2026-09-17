# Examples

Parameter files for the three illustrative examples reported in the accompanying
SoftwareX manuscript (Table 3 and Section "Illustrative examples"):

- [`absorber_case_params.json`](absorber_case_params.json) - grounded periodic absorber.
- [`transmitter_case_params.json`](transmitter_case_params.json) - conventional and complementary transmissive periodic cells.
- [`sensor_case_params.json`](sensor_case_params.json) - microstrip sensor with a complementary Gielis-CSRR.

Each file lists the Gielis, substrate, metal, concentric-geometry and simulation
parameters used to build that case, together with the discrete results quoted
in the manuscript (resonant frequencies, S-parameter values, absorptance).

To reproduce a case, launch `src/GielisMetaCST.mlapp`, enter the parameters from
the corresponding JSON file, and follow the mode-specific workflow described in
the [user manual](../docs/GielisMeta-CST_User_Manual.pdf).

Generated CST projects and full swept S-parameter exports are intentionally
excluded from version control because they depend on proprietary CST Studio
Suite software and can be large; the JSON files here record only the discrete
values reported in the manuscript, not the full simulated curves. Reusable
numerical exports may be added here in future tagged releases.
