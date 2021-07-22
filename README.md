# Online2DIrregularBPP
 My implementation of online 2D irregular BPP algorithm with state-of-the-art picking policy minimal surrounding waste.



**Licence**: The software as a whole is licenced under **GPL v3** because I'm using GPL v3-licenced library [libnfporb](https://github.com/kallaballa/libnfporb/), but for the everything except repository `source/nfp_interface` I'm granting **MIT** licence.  
+I would be happy if you wrote to me when you use my project because I'm curious if this will be useful for someone :)

Note: If you want to replace *libnfporb* library with your own implementation of No-fit polygon and Inner-fit polygon calculation, then you need to modify only the `geometry_tools.py` file (call your own functions, maybe modify error handling, ...) to make it work.



Usage:  run `run_tests.py` for a sample computation. If you choose `best_run`, then it runs on dataset generators  from `SFG_competition` using specified parameters. `euro_datasets` loads and runs specified datasets from `.csv` files.
