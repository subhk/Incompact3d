# ABL
set(case "ABL-Atmospheric-Boundary-Layer")
set(input_file "input_neutral_test.i3d")
set(additional_inputs "")
CreateMPITest(${test_dir} ${case} ${input_file} "${additional_inputs}")

