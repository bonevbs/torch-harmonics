# Coverage of torch-harmonics

Serial and distributed test suites combined, at eb8d057e54e3538f9382d5bb70aa6c83530475e2.
Written by the coverage job of tests.yml; do not edit.

| Name                                                                      |    Stmts |     Miss |   Cover |
|-------------------------------------------------------------------------- | -------: | -------: | ------: |
| torch\_harmonics/\_\_init\_\_.py                                          |       10 |        0 |    100% |
| torch\_harmonics/attention/\_\_init\_\_.py                                |        9 |        2 |     78% |
| torch\_harmonics/attention/\_attention\_utils.py                          |       58 |        0 |    100% |
| torch\_harmonics/attention/\_layout.py                                    |       36 |        4 |     89% |
| torch\_harmonics/attention/attention.py                                   |      208 |       20 |     90% |
| torch\_harmonics/attention/kernels\_torch/\_\_init\_\_.py                 |        0 |        0 |    100% |
| torch\_harmonics/attention/kernels\_torch/attention\_torch.py             |      395 |        4 |     99% |
| torch\_harmonics/attention/optimized/\_\_init\_\_.py                      |        0 |        0 |    100% |
| torch\_harmonics/attention/optimized/attention\_optimized.py              |       67 |        8 |     88% |
| torch\_harmonics/cache.py                                                 |       12 |        0 |    100% |
| torch\_harmonics/disco/\_\_init\_\_.py                                    |        9 |        2 |     78% |
| torch\_harmonics/disco/\_disco\_utils.py                                  |       19 |        0 |    100% |
| torch\_harmonics/disco/convolution.py                                     |      289 |       35 |     88% |
| torch\_harmonics/disco/kernels\_torch/\_\_init\_\_.py                     |        0 |        0 |    100% |
| torch\_harmonics/disco/kernels\_torch/disco\_torch.py                     |       53 |        0 |    100% |
| torch\_harmonics/disco/optimized/\_\_init\_\_.py                          |        0 |        0 |    100% |
| torch\_harmonics/disco/optimized/disco\_optimized.py                      |      454 |      162 |     64% |
| torch\_harmonics/distributed/\_\_init\_\_.py                              |        8 |        0 |    100% |
| torch\_harmonics/distributed/\_amp\_utils.py                              |       40 |       21 |     48% |
| torch\_harmonics/distributed/distributed\_attention.py                    |      464 |      420 |      9% |
| torch\_harmonics/distributed/distributed\_convolution.py                  |      206 |       19 |     91% |
| torch\_harmonics/distributed/distributed\_quadrature.py                   |       49 |        1 |     98% |
| torch\_harmonics/distributed/distributed\_resample.py                     |      105 |        7 |     93% |
| torch\_harmonics/distributed/distributed\_sht.py                          |      238 |        4 |     98% |
| torch\_harmonics/distributed/distributed\_spectral\_convolution.py        |       68 |        4 |     94% |
| torch\_harmonics/distributed/kernels/\_\_init\_\_.py                      |        1 |        0 |    100% |
| torch\_harmonics/distributed/kernels/distributed\_convolution\_kernels.py |       76 |       43 |     43% |
| torch\_harmonics/distributed/primitives.py                                |      622 |       82 |     87% |
| torch\_harmonics/distributed/utils.py                                     |       58 |        3 |     95% |
| torch\_harmonics/fft.py                                                   |       34 |        2 |     94% |
| torch\_harmonics/filter\_basis.py                                         |      306 |       28 |     91% |
| torch\_harmonics/legendre.py                                              |      103 |        5 |     95% |
| torch\_harmonics/quadrature.py                                            |      137 |        4 |     97% |
| torch\_harmonics/random\_fields.py                                        |       33 |        0 |    100% |
| torch\_harmonics/resample.py                                              |       74 |        2 |     97% |
| torch\_harmonics/sht.py                                                   |      133 |        4 |     97% |
| torch\_harmonics/spectral\_convolution.py                                 |       54 |        4 |     93% |
| torch\_harmonics/truncation.py                                            |       19 |        1 |     95% |
| torch\_harmonics/utils.py                                                 |       42 |       14 |     67% |
| **TOTAL**                                                                 | **4489** |  **905** | **80%** |
