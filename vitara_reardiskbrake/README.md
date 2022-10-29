# Suzuki Vitara / Suzuki Sidekick / GM Geo Tracker - Rear disk brake conversion

- Vitara come stock with rear drum brakes. Easiest way to convert it to rear disk brakes is to use Lancia/Fiat calipers (ex: Lancia Lybra) with stock Suzuki front disks.
- Lancia/Fiat calipers uses stock Suzuki handbrake cables and you don't need to use a proportioning valve.
- This tutorial will only work with later model axles (axle with wheel studs). For early model axles (studs on the brake drum) you need to design a disc adaptor.

### Materials

- Two Lancia/Fiat calipers (ex: Lancia Lybra)
- Two front Suzuki disks.
- You need a two brackets to support each caliper. [stl](vitara_reardiskbrake/bracket.stl) [dxf](vitara_reardiskbrake/bracket.dxf)
- Four spacers to space out the calipers. [stl](vitara_reardiskbrake/spacer.stl)
- Two handbrake spacers for the handbrake cables. [stl](vitara_reardiskbrake/handbrake.stl)
- Two generic brake lines and tee (Spanish built models don't have a stock tee).


#### Caliper bracket
```stl
solid Mesh
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 30.000000 0.000000
      vertex 2.311483 26.486357 0.000000
      vertex 2.448868 29.998724 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -3.551116 60.000000 0.000000
      vertex -7.617054 58.365650 0.000000
      vertex -10.897141 61.984760 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -95.339081 72.414757 0.000000
      vertex -94.041954 74.347336 0.000000
      vertex -93.972061 72.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 94.112053 0.000000
      vertex 45.588074 85.540596 0.000000
      vertex 45.558765 85.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 46.875835 65.689217 0.000000
      vertex 49.749855 80.065872 0.000000
      vertex 50.288071 80.007332 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 45.558765 85.000000 0.000000
      vertex 45.588074 84.459404 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 45.588074 84.459404 0.000000
      vertex 45.675663 83.925148 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 45.820496 83.403488 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex 45.675663 83.925148 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.308319 79.666428 0.000000
      vertex 53.795696 81.189194 0.000000
      vertex 54.188740 81.561508 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.308319 79.666428 0.000000
      vertex 54.188740 81.561508 0.000000
      vertex 54.539230 81.974129 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 45.675663 86.074852 0.000000
      vertex 45.588074 85.540596 0.000000
      vertex 25.003807 94.112053 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 45.820496 83.403488 0.000000
      vertex 46.020889 82.900551 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 46.020889 82.900551 0.000000
      vertex 46.274479 82.422234 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 46.578300 81.974129 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex 46.274479 82.422234 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 46.875835 65.689217 0.000000
      vertex 48.216724 80.582443 0.000000
      vertex 48.708073 80.355118 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 46.875835 65.689217 0.000000
      vertex 48.708073 80.355118 0.000000
      vertex 49.221119 80.182243 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 49.749855 80.065872 0.000000
      vertex 46.875835 65.689217 0.000000
      vertex 49.221119 80.182243 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 94.112053 0.000000
      vertex 47.321835 88.810806 0.000000
      vertex 46.928787 88.438499 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 94.112053 0.000000
      vertex 46.928787 88.438499 0.000000
      vertex 46.578300 88.025871 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 46.274479 87.577766 0.000000
      vertex 25.003807 94.112053 0.000000
      vertex 46.578300 88.025871 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 94.112053 0.000000
      vertex 46.274479 87.577766 0.000000
      vertex 46.020889 87.099449 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 94.112053 0.000000
      vertex 46.020889 87.099449 0.000000
      vertex 45.820496 86.596512 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 45.675663 86.074852 0.000000
      vertex 25.003807 94.112053 0.000000
      vertex 45.820496 86.596512 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 46.578300 81.974129 0.000000
      vertex 46.928787 81.561508 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 46.928787 81.561508 0.000000
      vertex 47.321835 81.189194 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 46.875835 65.689217 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex 47.321835 81.189194 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 46.875835 65.689217 0.000000
      vertex 47.321835 81.189194 0.000000
      vertex 47.752827 80.861557 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 48.216724 80.582443 0.000000
      vertex 46.875835 65.689217 0.000000
      vertex 47.752827 80.861557 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 46.875835 65.689217 0.000000
      vertex 50.288071 80.007332 0.000000
      vertex 50.829460 80.007332 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 46.875835 65.689217 0.000000
      vertex 50.829460 80.007332 0.000000
      vertex 51.367676 80.065872 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 51.896404 80.182243 0.000000
      vertex 46.875835 65.689217 0.000000
      vertex 51.367676 80.065872 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.308319 79.666428 0.000000
      vertex 54.539230 81.974129 0.000000
      vertex 54.843048 82.422234 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.308319 79.666428 0.000000
      vertex 54.843048 82.422234 0.000000
      vertex 55.096642 82.900551 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 61.763901 80.891975 0.000000
      vertex 61.308319 79.666428 0.000000
      vertex 55.096642 82.900551 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.763901 80.891975 0.000000
      vertex 55.096642 82.900551 0.000000
      vertex 55.297028 83.403488 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 62.087681 82.158730 0.000000
      vertex 61.763901 80.891975 0.000000
      vertex 55.297028 83.403488 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 62.087681 82.158730 0.000000
      vertex 55.297028 83.403488 0.000000
      vertex 55.441868 83.925148 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 62.276058 83.452576 0.000000
      vertex 62.087681 82.158730 0.000000
      vertex 55.441868 83.925148 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 62.276058 83.452576 0.000000
      vertex 55.441868 83.925148 0.000000
      vertex 55.529453 84.459404 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 62.326927 84.759064 0.000000
      vertex 62.276058 83.452576 0.000000
      vertex 55.529453 84.459404 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 62.326927 84.759064 0.000000
      vertex 55.529453 84.459404 0.000000
      vertex 55.558762 85.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 62.239719 86.063637 0.000000
      vertex 62.326927 84.759064 0.000000
      vertex 55.558762 85.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 62.239719 86.063637 0.000000
      vertex 55.558762 85.000000 0.000000
      vertex 55.529453 85.540596 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 62.015408 87.351730 0.000000
      vertex 62.239719 86.063637 0.000000
      vertex 55.529453 85.540596 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 62.015408 87.351730 0.000000
      vertex 55.529453 85.540596 0.000000
      vertex 55.441868 86.074852 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 61.656498 88.608986 0.000000
      vertex 62.015408 87.351730 0.000000
      vertex 55.441868 86.074852 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.656498 88.608986 0.000000
      vertex 55.441868 86.074852 0.000000
      vertex 55.297028 86.596512 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 61.166992 89.821373 0.000000
      vertex 61.656498 88.608986 0.000000
      vertex 55.297028 86.596512 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.166992 89.821373 0.000000
      vertex 55.297028 86.596512 0.000000
      vertex 55.096642 87.099449 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 60.552345 90.975380 0.000000
      vertex 61.166992 89.821373 0.000000
      vertex 55.096642 87.099449 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 60.552345 90.975380 0.000000
      vertex 55.096642 87.099449 0.000000
      vertex 54.843048 87.577766 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 59.819420 92.058121 0.000000
      vertex 60.552345 90.975380 0.000000
      vertex 54.843048 87.577766 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 59.819420 92.058121 0.000000
      vertex 54.843048 87.577766 0.000000
      vertex 54.539230 88.025871 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 58.976387 93.057526 0.000000
      vertex 59.819420 92.058121 0.000000
      vertex 54.539230 88.025871 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 58.976387 93.057526 0.000000
      vertex 54.539230 88.025871 0.000000
      vertex 54.188740 88.438499 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 58.032654 93.962448 0.000000
      vertex 58.976387 93.057526 0.000000
      vertex 54.188740 88.438499 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 58.032654 93.962448 0.000000
      vertex 54.188740 88.438499 0.000000
      vertex 53.795696 88.810806 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 56.998745 94.762787 0.000000
      vertex 58.032654 93.962448 0.000000
      vertex 53.795696 88.810806 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 56.998745 94.762787 0.000000
      vertex 53.795696 88.810806 0.000000
      vertex 53.364697 89.138451 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 55.886192 95.449615 0.000000
      vertex 56.998745 94.762787 0.000000
      vertex 53.364697 89.138451 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 55.886192 95.449615 0.000000
      vertex 53.364697 89.138451 0.000000
      vertex 52.900806 89.417564 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 54.707409 96.015282 0.000000
      vertex 55.886192 95.449615 0.000000
      vertex 52.900806 89.417564 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 54.707409 96.015282 0.000000
      vertex 52.900806 89.417564 0.000000
      vertex 52.409454 89.644890 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 53.475536 96.453468 0.000000
      vertex 54.707409 96.015282 0.000000
      vertex 52.409454 89.644890 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 53.475536 96.453468 0.000000
      vertex 52.409454 89.644890 0.000000
      vertex 51.896404 89.817749 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 52.204327 96.759293 0.000000
      vertex 53.475536 96.453468 0.000000
      vertex 51.896404 89.817749 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 52.204327 96.759293 0.000000
      vertex 51.896404 89.817749 0.000000
      vertex 51.367676 89.934135 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 50.907948 96.929337 0.000000
      vertex 52.204327 96.759293 0.000000
      vertex 51.367676 89.934135 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 50.907948 96.929337 0.000000
      vertex 51.367676 89.934135 0.000000
      vertex 50.829460 89.992668 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 49.600864 96.961708 0.000000
      vertex 50.907948 96.929337 0.000000
      vertex 50.829460 89.992668 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 49.600864 96.961708 0.000000
      vertex 50.829460 89.992668 0.000000
      vertex 50.288071 89.992668 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 49.600864 96.961708 0.000000
      vertex 50.288071 89.992668 0.000000
      vertex 49.749855 89.934135 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 49.221119 89.817749 0.000000
      vertex 49.600864 96.961708 0.000000
      vertex 49.749855 89.934135 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 46.875835 65.689217 0.000000
      vertex 51.896404 80.182243 0.000000
      vertex 52.409454 80.355118 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 46.875835 65.689217 0.000000
      vertex 52.409454 80.355118 0.000000
      vertex 52.900806 80.582443 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 61.308319 79.666428 0.000000
      vertex 46.875835 65.689217 0.000000
      vertex 52.900806 80.582443 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.308319 79.666428 0.000000
      vertex 52.900806 80.582443 0.000000
      vertex 53.364697 80.861557 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 53.795696 81.189194 0.000000
      vertex 61.308319 79.666428 0.000000
      vertex 53.364697 80.861557 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 49.600864 96.961708 0.000000
      vertex 49.221119 89.817749 0.000000
      vertex 48.708073 89.644890 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 49.600864 96.961708 0.000000
      vertex 48.708073 89.644890 0.000000
      vertex 48.216724 89.417564 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 94.112053 0.000000
      vertex 49.600864 96.961708 0.000000
      vertex 48.216724 89.417564 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 94.112053 0.000000
      vertex 48.216724 89.417564 0.000000
      vertex 47.752827 89.138451 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 47.321835 88.810806 0.000000
      vertex 25.003807 94.112053 0.000000
      vertex 47.752827 89.138451 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 94.112053 0.000000
      vertex 45.558765 85.000000 0.000000
      vertex 25.003807 72.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 25.003807 94.112053 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex -27.297455 72.335861 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -31.975719 73.739693 0.000000
      vertex 25.003807 94.112053 0.000000
      vertex -27.297455 72.335861 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 94.112053 0.000000
      vertex -31.975719 73.739693 0.000000
      vertex -36.778576 74.628212 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 94.112053 0.000000
      vertex -36.778576 74.628212 0.000000
      vertex -41.649437 74.990967 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -84.934654 81.375298 0.000000
      vertex 25.003807 94.112053 0.000000
      vertex -41.649437 74.990967 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -56.096283 72.913033 0.000000
      vertex -94.041954 74.347336 0.000000
      vertex -92.544991 76.129631 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -56.096283 72.913033 0.000000
      vertex -92.544991 76.129631 0.000000
      vertex -90.865486 77.741058 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -84.934654 81.375298 0.000000
      vertex -41.649437 74.990967 0.000000
      vertex -46.530926 74.823669 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -84.934654 81.375298 0.000000
      vertex -46.530926 74.823669 0.000000
      vertex -51.365528 74.128296 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -87.038231 80.379112 0.000000
      vertex -84.934654 81.375298 0.000000
      vertex -51.365528 74.128296 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -87.038231 80.379112 0.000000
      vertex -51.365528 74.128296 0.000000
      vertex -56.096283 72.913033 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -89.022804 79.163017 0.000000
      vertex -87.038231 80.379112 0.000000
      vertex -56.096283 72.913033 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex -89.022804 79.163017 0.000000
      vertex -56.096283 72.913033 0.000000
      vertex -90.865486 77.741058 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -98.392998 30.000000 0.000000
      vertex -98.392998 61.323826 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -98.392998 61.323826 0.000000
      vertex -98.267982 63.648006 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex -97.894371 65.945366 0.000000
      vertex -93.972061 72.000000 0.000000
      vertex -98.267982 63.648006 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -97.894371 65.945366 0.000000
      vertex -97.276474 68.189384 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -97.276474 68.189384 0.000000
      vertex -96.421417 70.354179 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex -95.339081 72.414757 0.000000
      vertex -93.972061 72.000000 0.000000
      vertex -96.421417 70.354179 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -94.147072 -7.809444 0.000000
      vertex -95.028343 -7.076672 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -95.028343 -7.076672 0.000000
      vertex -95.825218 -6.252914 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -96.528366 -5.347826 0.000000
      vertex -93.972061 30.000000 0.000000
      vertex -95.825218 -6.252914 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -97.999008 -2.254716 0.000000
      vertex -98.257126 -1.138039 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -98.257126 -1.138039 0.000000
      vertex -98.392998 -0.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -98.392998 30.000000 0.000000
      vertex -93.972061 30.000000 0.000000
      vertex -98.392998 -0.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -96.528366 -5.347826 0.000000
      vertex -97.129532 -4.372022 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -97.129532 -4.372022 0.000000
      vertex -97.621666 -3.336940 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -97.999008 -2.254716 0.000000
      vertex -93.972061 30.000000 0.000000
      vertex -97.621666 -3.336940 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -89.527679 -0.432476 0.000000
      vertex -94.147072 -7.809444 0.000000
      vertex -89.551132 -0.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -87.518509 28.286697 0.000000
      vertex -87.067932 23.423172 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -87.067932 23.423172 0.000000
      vertex -86.092896 18.637129 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -80.165909 5.299218 0.000000
      vertex -81.574585 -0.432476 0.000000
      vertex -81.551132 -0.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -80.165909 5.299218 0.000000
      vertex -81.551132 -0.000000 0.000000
      vertex -81.574585 0.432476 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -82.621429 9.521455 0.000000
      vertex -80.165909 5.299218 0.000000
      vertex -81.574585 0.432476 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -82.621429 9.521455 0.000000
      vertex -81.574585 0.432476 0.000000
      vertex -81.644646 0.859882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -84.604889 13.984954 0.000000
      vertex -82.621429 9.521455 0.000000
      vertex -81.644646 0.859882 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex -84.604889 13.984954 0.000000
      vertex -81.644646 0.859882 0.000000
      vertex -86.092896 18.637129 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -89.181427 1.679556 0.000000
      vertex -89.341743 1.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -89.341743 1.277206 0.000000
      vertex -89.457619 0.859882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -94.147072 -7.809444 0.000000
      vertex -93.972061 30.000000 0.000000
      vertex -89.457619 0.859882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -94.147072 -7.809444 0.000000
      vertex -89.457619 0.859882 0.000000
      vertex -89.527679 0.432476 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -89.551132 -0.000000 0.000000
      vertex -94.147072 -7.809444 0.000000
      vertex -89.527679 0.432476 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -94.147072 -7.809444 0.000000
      vertex -89.527679 -0.432476 0.000000
      vertex -89.457619 -0.859882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -94.147072 -7.809444 0.000000
      vertex -89.457619 -0.859882 0.000000
      vertex -89.341743 -1.277206 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -89.181427 -1.679556 0.000000
      vertex -94.147072 -7.809444 0.000000
      vertex -89.341743 -1.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -82.366760 2.420697 0.000000
      vertex -82.647156 2.750798 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -82.647156 2.750798 0.000000
      vertex -82.961586 3.048648 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -82.961586 3.048648 0.000000
      vertex -83.306389 3.310756 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -83.677498 3.534048 0.000000
      vertex -93.972061 30.000000 0.000000
      vertex -83.306389 3.310756 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -86.092896 18.637129 0.000000
      vertex -81.644646 0.859882 0.000000
      vertex -81.760521 1.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -86.092896 18.637129 0.000000
      vertex -81.760521 1.277206 0.000000
      vertex -81.920830 1.679556 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -86.092896 18.637129 0.000000
      vertex -81.920830 1.679556 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -81.920830 1.679556 0.000000
      vertex -82.123703 2.062216 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -82.366760 2.420697 0.000000
      vertex -93.972061 30.000000 0.000000
      vertex -82.123703 2.062216 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -83.677498 3.534048 0.000000
      vertex -84.070580 3.715907 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -84.070580 3.715907 0.000000
      vertex -84.481018 3.854200 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -84.904007 3.947306 0.000000
      vertex -93.972061 30.000000 0.000000
      vertex -84.481018 3.854200 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -84.904007 3.947306 0.000000
      vertex -85.334579 3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -85.334579 3.994134 0.000000
      vertex -85.767685 3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -86.198265 3.947306 0.000000
      vertex -93.972061 30.000000 0.000000
      vertex -85.767685 3.994134 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -77.601768 -2.040565 0.000000
      vertex -77.956306 -3.130472 0.000000
      vertex -81.760521 -1.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -77.601768 -2.040565 0.000000
      vertex -81.760521 -1.277206 0.000000
      vertex -81.644646 -0.859882 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -77.367149 -0.918714 0.000000
      vertex -77.601768 -2.040565 0.000000
      vertex -81.644646 -0.859882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -77.367149 -0.918714 0.000000
      vertex -81.644646 -0.859882 0.000000
      vertex -77.255203 0.221927 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -86.198265 3.947306 0.000000
      vertex -86.621246 3.854200 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -86.621246 3.854200 0.000000
      vertex -87.031685 3.715907 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -87.424759 3.534048 0.000000
      vertex -93.972061 30.000000 0.000000
      vertex -87.031685 3.715907 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -87.424759 3.534048 0.000000
      vertex -87.795883 3.310756 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -87.795883 3.310756 0.000000
      vertex -88.140671 3.048648 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -88.455109 2.750798 0.000000
      vertex -93.972061 30.000000 0.000000
      vertex -88.140671 3.048648 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.191734 -8.442637 0.000000
      vertex -94.147072 -7.809444 0.000000
      vertex -88.455109 -2.750798 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.191734 -8.442637 0.000000
      vertex -88.455109 -2.750798 0.000000
      vertex -88.140671 -3.048648 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -92.173546 -8.968830 0.000000
      vertex -93.191734 -8.442637 0.000000
      vertex -88.140671 -3.048648 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -92.173546 -8.968830 0.000000
      vertex -88.140671 -3.048648 0.000000
      vertex -87.795883 -3.310756 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -91.104431 -9.381852 0.000000
      vertex -92.173546 -8.968830 0.000000
      vertex -87.795883 -3.310756 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -91.104431 -9.381852 0.000000
      vertex -87.795883 -3.310756 0.000000
      vertex -87.424759 -3.534048 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -89.996925 -9.676861 0.000000
      vertex -91.104431 -9.381852 0.000000
      vertex -87.424759 -3.534048 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -89.996925 -9.676861 0.000000
      vertex -87.424759 -3.534048 0.000000
      vertex -87.031685 -3.715907 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -88.864021 -9.850399 0.000000
      vertex -89.996925 -9.676861 0.000000
      vertex -87.031685 -3.715907 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -88.864021 -9.850399 0.000000
      vertex -87.031685 -3.715907 0.000000
      vertex -86.621246 -3.854200 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -87.718994 -9.900431 0.000000
      vertex -88.864021 -9.850399 0.000000
      vertex -86.621246 -3.854200 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -87.718994 -9.900431 0.000000
      vertex -86.621246 -3.854200 0.000000
      vertex -86.198265 -3.947306 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -86.575264 -9.826368 0.000000
      vertex -87.718994 -9.900431 0.000000
      vertex -86.198265 -3.947306 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -86.575264 -9.826368 0.000000
      vertex -86.198265 -3.947306 0.000000
      vertex -85.767685 -3.994134 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -85.446251 -9.629083 0.000000
      vertex -86.575264 -9.826368 0.000000
      vertex -85.767685 -3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -85.446251 -9.629083 0.000000
      vertex -85.767685 -3.994134 0.000000
      vertex -85.334579 -3.994134 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -84.345184 -9.310886 0.000000
      vertex -85.446251 -9.629083 0.000000
      vertex -85.334579 -3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -84.345184 -9.310886 0.000000
      vertex -85.334579 -3.994134 0.000000
      vertex -84.904007 -3.947306 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -83.284981 -8.875509 0.000000
      vertex -84.345184 -9.310886 0.000000
      vertex -84.904007 -3.947306 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -83.284981 -8.875509 0.000000
      vertex -84.904007 -3.947306 0.000000
      vertex -84.481018 -3.854200 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -82.278061 -8.328054 0.000000
      vertex -83.284981 -8.875509 0.000000
      vertex -84.481018 -3.854200 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -82.278061 -8.328054 0.000000
      vertex -84.481018 -3.854200 0.000000
      vertex -84.070580 -3.715907 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -81.336227 -7.674942 0.000000
      vertex -82.278061 -8.328054 0.000000
      vertex -84.070580 -3.715907 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.336227 -7.674942 0.000000
      vertex -84.070580 -3.715907 0.000000
      vertex -83.677498 -3.534048 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -80.470543 -6.923829 0.000000
      vertex -81.336227 -7.674942 0.000000
      vertex -83.677498 -3.534048 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -80.470543 -6.923829 0.000000
      vertex -83.677498 -3.534048 0.000000
      vertex -83.306389 -3.310756 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -79.691124 -6.083521 0.000000
      vertex -80.470543 -6.923829 0.000000
      vertex -83.306389 -3.310756 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -94.147072 -7.809444 0.000000
      vertex -89.181427 -1.679556 0.000000
      vertex -88.978561 -2.062216 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -94.147072 -7.809444 0.000000
      vertex -88.978561 -2.062216 0.000000
      vertex -88.735504 -2.420697 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -88.455109 -2.750798 0.000000
      vertex -94.147072 -7.809444 0.000000
      vertex -88.735504 -2.420697 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.644646 -0.859882 0.000000
      vertex -81.574585 -0.432476 0.000000
      vertex -80.165909 5.299218 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.644646 -0.859882 0.000000
      vertex -80.165909 5.299218 0.000000
      vertex -77.267235 1.367985 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -77.255203 0.221927 0.000000
      vertex -81.644646 -0.859882 0.000000
      vertex -77.267235 1.367985 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -88.455109 2.750798 0.000000
      vertex -88.735504 2.420697 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -88.735504 2.420697 0.000000
      vertex -88.978561 2.062216 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -89.181427 1.679556 0.000000
      vertex -93.972061 30.000000 0.000000
      vertex -88.978561 2.062216 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -79.691124 -6.083521 0.000000
      vertex -83.306389 -3.310756 0.000000
      vertex -82.961586 -3.048648 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -79.691124 -6.083521 0.000000
      vertex -82.961586 -3.048648 0.000000
      vertex -82.647156 -2.750798 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -79.007141 -5.163870 0.000000
      vertex -79.691124 -6.083521 0.000000
      vertex -82.647156 -2.750798 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -79.007141 -5.163870 0.000000
      vertex -82.647156 -2.750798 0.000000
      vertex -82.366760 -2.420697 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -78.426598 -4.175659 0.000000
      vertex -79.007141 -5.163870 0.000000
      vertex -82.366760 -2.420697 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -78.426598 -4.175659 0.000000
      vertex -82.366760 -2.420697 0.000000
      vertex -82.123703 -2.062216 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -77.956306 -3.130472 0.000000
      vertex -78.426598 -4.175659 0.000000
      vertex -82.123703 -2.062216 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -77.956306 -3.130472 0.000000
      vertex -82.123703 -2.062216 0.000000
      vertex -81.920830 -1.679556 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex -81.760521 -1.277206 0.000000
      vertex -77.956306 -3.130472 0.000000
      vertex -81.920830 -1.679556 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -94.041954 74.347336 0.000000
      vertex -56.096283 72.913033 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -56.096283 72.913033 0.000000
      vertex -60.667461 71.192215 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -65.025208 68.986099 0.000000
      vertex -93.972061 72.000000 0.000000
      vertex -60.667461 71.192215 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -65.025208 68.986099 0.000000
      vertex -69.118179 66.320679 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -69.118179 66.320679 0.000000
      vertex -72.898163 63.227364 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -76.320625 59.742584 0.000000
      vertex -93.972061 72.000000 0.000000
      vertex -72.898163 63.227364 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -89.527664 59.567524 0.000000
      vertex -93.972061 72.000000 0.000000
      vertex -89.551117 60.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -98.392998 30.000000 0.000000
      vertex -93.972061 72.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -93.972061 72.000000 0.000000
      vertex -85.701576 42.768681 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -86.831276 38.016766 0.000000
      vertex -93.972061 30.000000 0.000000
      vertex -85.701576 42.768681 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -86.831276 38.016766 0.000000
      vertex -87.439316 33.170410 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 30.000000 0.000000
      vertex -87.439316 33.170410 0.000000
      vertex -87.551132 30.000978 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -87.518509 28.286697 0.000000
      vertex -93.972061 30.000000 0.000000
      vertex -87.551132 30.000978 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -89.527664 59.567524 0.000000
      vertex -89.457603 59.140121 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -89.457603 59.140121 0.000000
      vertex -89.341728 58.722794 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -85.701576 42.768681 0.000000
      vertex -93.972061 72.000000 0.000000
      vertex -89.341728 58.722794 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -85.701576 42.768681 0.000000
      vertex -89.341728 58.722794 0.000000
      vertex -89.181419 58.320442 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -84.063507 47.370163 0.000000
      vertex -85.701576 42.768681 0.000000
      vertex -89.181419 58.320442 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -84.063507 47.370163 0.000000
      vertex -89.181419 58.320442 0.000000
      vertex -88.978546 57.937786 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex -88.735489 57.579300 0.000000
      vertex -84.063507 47.370163 0.000000
      vertex -88.978546 57.937786 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -79.345238 55.907406 0.000000
      vertex -82.366745 57.579300 0.000000
      vertex -82.123688 57.937786 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -79.345238 55.907406 0.000000
      vertex -82.123688 57.937786 0.000000
      vertex -81.920815 58.320442 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -79.345238 55.907406 0.000000
      vertex -81.920815 58.320442 0.000000
      vertex -81.760506 58.722794 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -76.320625 59.742584 0.000000
      vertex -79.345238 55.907406 0.000000
      vertex -81.760506 58.722794 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -76.320625 59.742584 0.000000
      vertex -81.760506 58.722794 0.000000
      vertex -81.644630 59.140121 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -76.320625 59.742584 0.000000
      vertex -81.644630 59.140121 0.000000
      vertex -81.574570 59.567524 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -76.320625 59.742584 0.000000
      vertex -81.574570 59.567524 0.000000
      vertex -81.551109 60.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.574570 60.432476 0.000000
      vertex -76.320625 59.742584 0.000000
      vertex -81.551109 60.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -84.063507 47.370163 0.000000
      vertex -88.735489 57.579300 0.000000
      vertex -88.455093 57.249203 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -84.063507 47.370163 0.000000
      vertex -88.455093 57.249203 0.000000
      vertex -88.140656 56.951351 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -81.936371 51.767002 0.000000
      vertex -84.063507 47.370163 0.000000
      vertex -88.140656 56.951351 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.936371 51.767002 0.000000
      vertex -88.140656 56.951351 0.000000
      vertex -87.795860 56.689243 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.936371 51.767002 0.000000
      vertex -87.795860 56.689243 0.000000
      vertex -87.424751 56.465954 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.936371 51.767002 0.000000
      vertex -87.424751 56.465954 0.000000
      vertex -87.031670 56.284092 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex -86.621231 56.145798 0.000000
      vertex -81.936371 51.767002 0.000000
      vertex -87.031670 56.284092 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.936371 51.767002 0.000000
      vertex -84.070564 56.284092 0.000000
      vertex -83.677475 56.465954 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.936371 51.767002 0.000000
      vertex -86.621231 56.145798 0.000000
      vertex -86.198242 56.052692 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.936371 51.767002 0.000000
      vertex -86.198242 56.052692 0.000000
      vertex -85.767670 56.005867 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex -85.334564 56.005867 0.000000
      vertex -81.936371 51.767002 0.000000
      vertex -85.767670 56.005867 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.936371 51.767002 0.000000
      vertex -85.334564 56.005867 0.000000
      vertex -84.903984 56.052692 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.936371 51.767002 0.000000
      vertex -84.903984 56.052692 0.000000
      vertex -84.481003 56.145798 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex -84.070564 56.284092 0.000000
      vertex -81.936371 51.767002 0.000000
      vertex -84.481003 56.145798 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -76.320625 59.742584 0.000000
      vertex -81.574570 60.432476 0.000000
      vertex -81.644630 60.859882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -76.320625 59.742584 0.000000
      vertex -81.644630 60.859882 0.000000
      vertex -81.760506 61.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.920815 61.679558 0.000000
      vertex -76.320625 59.742584 0.000000
      vertex -81.760506 61.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -76.320625 59.742584 0.000000
      vertex -81.920815 61.679558 0.000000
      vertex -82.123688 62.062214 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -76.320625 59.742584 0.000000
      vertex -82.123688 62.062214 0.000000
      vertex -82.366745 62.420696 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -82.647133 62.750801 0.000000
      vertex -76.320625 59.742584 0.000000
      vertex -82.366745 62.420696 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -84.070564 63.715904 0.000000
      vertex -84.481003 63.854202 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -84.481003 63.854202 0.000000
      vertex -84.903984 63.947304 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -85.334564 63.994133 0.000000
      vertex -93.972061 72.000000 0.000000
      vertex -84.903984 63.947304 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -85.334564 63.994133 0.000000
      vertex -85.767670 63.994133 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -85.767670 63.994133 0.000000
      vertex -86.198242 63.947304 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -86.621231 63.854202 0.000000
      vertex -93.972061 72.000000 0.000000
      vertex -86.198242 63.947304 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -86.621231 63.854202 0.000000
      vertex -87.031670 63.715904 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -87.031670 63.715904 0.000000
      vertex -87.424751 63.534050 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -87.795860 63.310757 0.000000
      vertex -93.972061 72.000000 0.000000
      vertex -87.424751 63.534050 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -87.795860 63.310757 0.000000
      vertex -88.140656 63.048645 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -88.140656 63.048645 0.000000
      vertex -88.455093 62.750801 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -88.735489 62.420696 0.000000
      vertex -93.972061 72.000000 0.000000
      vertex -88.455093 62.750801 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -88.735489 62.420696 0.000000
      vertex -88.978546 62.062214 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -88.978546 62.062214 0.000000
      vertex -89.181419 61.679558 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -89.341728 61.277206 0.000000
      vertex -93.972061 72.000000 0.000000
      vertex -89.181419 61.679558 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -89.341728 61.277206 0.000000
      vertex -89.457603 60.859882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -89.457603 60.859882 0.000000
      vertex -89.527664 60.432476 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -89.551117 60.000000 0.000000
      vertex -93.972061 72.000000 0.000000
      vertex -89.527664 60.432476 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.936371 51.767002 0.000000
      vertex -83.677475 56.465954 0.000000
      vertex -83.306366 56.689243 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -81.936371 51.767002 0.000000
      vertex -83.306366 56.689243 0.000000
      vertex -82.961563 56.951351 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -79.345238 55.907406 0.000000
      vertex -81.936371 51.767002 0.000000
      vertex -82.961563 56.951351 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -79.345238 55.907406 0.000000
      vertex -82.961563 56.951351 0.000000
      vertex -82.647133 57.249203 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex -82.366745 57.579300 0.000000
      vertex -79.345238 55.907406 0.000000
      vertex -82.647133 57.249203 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -76.320625 59.742584 0.000000
      vertex -82.647133 62.750801 0.000000
      vertex -82.961563 63.048645 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -76.320625 59.742584 0.000000
      vertex -82.961563 63.048645 0.000000
      vertex -83.306366 63.310757 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -76.320625 59.742584 0.000000
      vertex -83.306366 63.310757 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -93.972061 72.000000 0.000000
      vertex -83.306366 63.310757 0.000000
      vertex -83.677475 63.534050 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -84.070564 63.715904 0.000000
      vertex -93.972061 72.000000 0.000000
      vertex -83.677475 63.534050 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 30.000000 0.000000
      vertex 2.448868 29.998724 0.000000
      vertex 2.428029 31.369322 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 30.000000 0.000000
      vertex 2.428029 31.369322 0.000000
      vertex 2.014667 36.236149 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 25.003807 30.000000 0.000000
      vertex 2.014667 36.236149 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 2.014667 36.236149 0.000000
      vertex 1.076266 41.029510 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 1.076266 41.029510 0.000000
      vertex -0.376117 45.692932 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -2.325371 50.171467 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex -0.376117 45.692932 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex -14.550149 65.227043 0.000000
      vertex -18.533041 68.054321 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex -18.533041 68.054321 0.000000
      vertex -22.798897 70.433266 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -27.297455 72.335861 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex -22.798897 70.433266 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -3.527667 60.432476 0.000000
      vertex -3.551116 60.000000 0.000000
      vertex -10.897141 61.984760 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -4.748533 54.412365 0.000000
      vertex -3.341728 58.722794 0.000000
      vertex -3.181417 58.320442 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex -0.621229 56.145798 0.000000
      vertex -0.198244 56.052692 0.000000
      vertex -2.325371 50.171467 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -0.621229 56.145798 0.000000
      vertex -2.325371 50.171467 0.000000
      vertex -1.031668 56.284092 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -2.325371 50.171467 0.000000
      vertex -0.198244 56.052692 0.000000
      vertex 0.232329 56.005867 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -2.325371 50.171467 0.000000
      vertex 0.232329 56.005867 0.000000
      vertex 0.665440 56.005867 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 1.096012 56.052692 0.000000
      vertex -2.325371 50.171467 0.000000
      vertex 0.665440 56.005867 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex -3.457598 59.140121 0.000000
      vertex -3.341728 58.722794 0.000000
      vertex -4.748533 54.412365 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -4.748533 54.412365 0.000000
      vertex -3.181417 58.320442 0.000000
      vertex -2.978544 57.937786 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -4.748533 54.412365 0.000000
      vertex -2.978544 57.937786 0.000000
      vertex -2.735488 57.579300 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -2.455098 57.249203 0.000000
      vertex -4.748533 54.412365 0.000000
      vertex -2.735488 57.579300 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 0.665440 63.994133 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex 1.096012 63.947304 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -4.748533 54.412365 0.000000
      vertex -7.617054 58.365650 0.000000
      vertex -3.551116 60.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -4.748533 54.412365 0.000000
      vertex -3.551116 60.000000 0.000000
      vertex -3.527667 59.567524 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -3.457598 59.140121 0.000000
      vertex -4.748533 54.412365 0.000000
      vertex -3.527667 59.567524 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -4.748533 54.412365 0.000000
      vertex -2.455098 57.249203 0.000000
      vertex -2.140661 56.951351 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -4.748533 54.412365 0.000000
      vertex -2.140661 56.951351 0.000000
      vertex -1.795864 56.689243 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -2.325371 50.171467 0.000000
      vertex -4.748533 54.412365 0.000000
      vertex -1.795864 56.689243 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -2.325371 50.171467 0.000000
      vertex -1.795864 56.689243 0.000000
      vertex -1.424749 56.465954 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -1.031668 56.284092 0.000000
      vertex -2.325371 50.171467 0.000000
      vertex -1.424749 56.465954 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 3.038430 63.048645 0.000000
      vertex 2.693633 63.310757 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 2.693633 63.310757 0.000000
      vertex 2.322518 63.534050 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 4.355367 59.140121 0.000000
      vertex 4.425436 59.567524 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 4.425436 59.567524 0.000000
      vertex 4.448884 60.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 4.425436 60.432476 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex 4.448884 60.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 2.322518 63.534050 0.000000
      vertex 1.929437 63.715904 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 1.929437 63.715904 0.000000
      vertex 1.518998 63.854202 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 1.096012 63.947304 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex 1.518998 63.854202 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.876313 62.062214 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex 4.079186 61.679558 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 0.665440 63.994133 0.000000
      vertex 0.232329 63.994133 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 0.232329 63.994133 0.000000
      vertex -0.198244 63.947304 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -14.550149 65.227043 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex -0.198244 63.947304 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -14.550149 65.227043 0.000000
      vertex -0.198244 63.947304 0.000000
      vertex -0.621229 63.854202 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -1.031668 63.715904 0.000000
      vertex -14.550149 65.227043 0.000000
      vertex -0.621229 63.854202 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -14.550149 65.227043 0.000000
      vertex -1.031668 63.715904 0.000000
      vertex -1.424749 63.534050 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -14.550149 65.227043 0.000000
      vertex -1.424749 63.534050 0.000000
      vertex -1.795864 63.310757 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -2.140661 63.048645 0.000000
      vertex -14.550149 65.227043 0.000000
      vertex -1.795864 63.310757 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -2.325371 50.171467 0.000000
      vertex 1.096012 56.052692 0.000000
      vertex 1.518998 56.145798 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -2.325371 50.171467 0.000000
      vertex 1.518998 56.145798 0.000000
      vertex 1.929437 56.284092 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 2.322518 56.465954 0.000000
      vertex -2.325371 50.171467 0.000000
      vertex 1.929437 56.284092 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 3.633257 57.579300 0.000000
      vertex 3.876313 57.937786 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 4.425436 60.432476 0.000000
      vertex 4.355367 60.859882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 4.355367 60.859882 0.000000
      vertex 4.239497 61.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 4.079186 61.679558 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex 4.239497 61.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 3.876313 62.062214 0.000000
      vertex 3.633257 62.420696 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 3.633257 62.420696 0.000000
      vertex 3.352866 62.750801 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.038430 63.048645 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex 3.352866 62.750801 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -14.550149 65.227043 0.000000
      vertex -2.140661 63.048645 0.000000
      vertex -2.455098 62.750801 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -14.550149 65.227043 0.000000
      vertex -2.455098 62.750801 0.000000
      vertex -2.735488 62.420696 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -2.978544 62.062214 0.000000
      vertex -14.550149 65.227043 0.000000
      vertex -2.735488 62.420696 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -14.550149 65.227043 0.000000
      vertex -2.978544 62.062214 0.000000
      vertex -3.181417 61.679558 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -14.550149 65.227043 0.000000
      vertex -3.181417 61.679558 0.000000
      vertex -3.341728 61.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -10.897141 61.984760 0.000000
      vertex -14.550149 65.227043 0.000000
      vertex -3.341728 61.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -10.897141 61.984760 0.000000
      vertex -3.341728 61.277206 0.000000
      vertex -3.457598 60.859882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -3.527667 60.432476 0.000000
      vertex -10.897141 61.984760 0.000000
      vertex -3.457598 60.859882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -2.325371 50.171467 0.000000
      vertex 2.322518 56.465954 0.000000
      vertex 2.693633 56.689243 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -2.325371 50.171467 0.000000
      vertex 2.693633 56.689243 0.000000
      vertex 3.038430 56.951351 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex -2.325371 50.171467 0.000000
      vertex 3.038430 56.951351 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 3.038430 56.951351 0.000000
      vertex 3.352866 57.249203 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 3.633257 57.579300 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex 3.352866 57.249203 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 3.876313 57.937786 0.000000
      vertex 4.079186 58.320442 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 4.079186 58.320442 0.000000
      vertex 4.239497 58.722794 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 4.355367 59.140121 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex 4.239497 58.722794 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex -3.333524 7.932395 0.000000
      vertex -1.172825 12.312838 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex -1.172825 12.312838 0.000000
      vertex 0.500388 16.901657 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 25.003807 30.000000 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 0.500388 16.901657 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 30.000000 0.000000
      vertex 0.500388 16.901657 0.000000
      vertex 1.666403 21.644791 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 2.311483 26.486357 0.000000
      vertex 25.003807 30.000000 0.000000
      vertex 1.666403 21.644791 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -5.956253 3.811934 0.000000
      vertex -0.621246 3.854200 0.000000
      vertex -1.031685 3.715907 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 1.434067 -12.024600 0.000000
      vertex 1.518981 -3.854200 0.000000
      vertex 1.929420 -3.715907 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -5.023365 -6.493875 0.000000
      vertex -2.140677 -3.048648 0.000000
      vertex -1.795881 -3.310756 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 1.095996 -3.947306 0.000000
      vertex 1.518981 -3.854200 0.000000
      vertex 1.434067 -12.024600 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -5.956253 3.811934 0.000000
      vertex -1.031685 3.715907 0.000000
      vertex -1.424766 3.534048 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -5.956253 3.811934 0.000000
      vertex -1.424766 3.534048 0.000000
      vertex -1.795881 3.310756 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -2.140677 3.048648 0.000000
      vertex -5.956253 3.811934 0.000000
      vertex -1.795881 3.310756 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -5.956253 3.811934 0.000000
      vertex -2.140677 3.048648 0.000000
      vertex -2.455114 2.750798 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -5.956253 3.811934 0.000000
      vertex -2.455114 2.750798 0.000000
      vertex -2.735505 2.420697 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -2.978561 2.062216 0.000000
      vertex -5.956253 3.811934 0.000000
      vertex -2.735505 2.420697 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -9.010113 0.000000 0.000000
      vertex -3.527684 0.432476 0.000000
      vertex -3.551132 -0.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -9.010113 0.000000 0.000000
      vertex -3.551132 -0.000000 0.000000
      vertex -3.527684 -0.432476 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -7.896352 -2.291907 0.000000
      vertex -9.010113 0.000000 0.000000
      vertex -3.527684 -0.432476 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -1.031685 -3.715907 0.000000
      vertex -1.385300 -10.054082 0.000000
      vertex -3.291848 -8.363408 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 2.322501 -3.534048 0.000000
      vertex 2.693616 -3.310756 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 2.693616 -3.310756 0.000000
      vertex 3.038413 -3.048648 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 3.352849 -2.750798 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 3.038413 -3.048648 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -5.956253 3.811934 0.000000
      vertex -2.978561 2.062216 0.000000
      vertex -3.181434 1.679556 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -5.956253 3.811934 0.000000
      vertex -3.181434 1.679556 0.000000
      vertex -3.341745 1.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -9.010113 0.000000 0.000000
      vertex -5.956253 3.811934 0.000000
      vertex -3.341745 1.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -9.010113 0.000000 0.000000
      vertex -3.341745 1.277206 0.000000
      vertex -3.457615 0.859882 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -3.527684 0.432476 0.000000
      vertex -9.010113 0.000000 0.000000
      vertex -3.457615 0.859882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -7.896352 -2.291907 0.000000
      vertex -3.527684 -0.432476 0.000000
      vertex -3.457615 -0.859882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -7.896352 -2.291907 0.000000
      vertex -3.457615 -0.859882 0.000000
      vertex -3.341745 -1.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -6.563149 -4.463514 0.000000
      vertex -7.896352 -2.291907 0.000000
      vertex -3.341745 -1.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -6.563149 -4.463514 0.000000
      vertex -3.341745 -1.277206 0.000000
      vertex -3.181434 -1.679556 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -3.291848 -8.363408 0.000000
      vertex -5.023365 -6.493875 0.000000
      vertex -1.795881 -3.310756 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -3.291848 -8.363408 0.000000
      vertex -1.795881 -3.310756 0.000000
      vertex -1.424766 -3.534048 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -1.031685 -3.715907 0.000000
      vertex -3.291848 -8.363408 0.000000
      vertex -1.424766 -3.534048 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 3.352849 -2.750798 0.000000
      vertex 3.633240 -2.420697 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 3.633240 -2.420697 0.000000
      vertex 3.876296 -2.062216 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 4.079169 -1.679556 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 3.876296 -2.062216 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 4.079169 -1.679556 0.000000
      vertex 4.239480 -1.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 4.239480 -1.277206 0.000000
      vertex 4.355350 -0.859882 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 4.425419 -0.432476 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 4.355350 -0.859882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -3.333524 7.932395 0.000000
      vertex 1.929420 3.715907 0.000000
      vertex 1.518981 3.854200 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -3.333524 7.932395 0.000000
      vertex 1.518981 3.854200 0.000000
      vertex 1.095996 3.947306 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -6.563149 -4.463514 0.000000
      vertex -3.181434 -1.679556 0.000000
      vertex -2.978561 -2.062216 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -6.563149 -4.463514 0.000000
      vertex -2.978561 -2.062216 0.000000
      vertex -2.735505 -2.420697 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -5.023365 -6.493875 0.000000
      vertex -6.563149 -4.463514 0.000000
      vertex -2.735505 -2.420697 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -5.023365 -6.493875 0.000000
      vertex -2.735505 -2.420697 0.000000
      vertex -2.455114 -2.750798 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -2.140677 -3.048648 0.000000
      vertex -5.023365 -6.493875 0.000000
      vertex -2.455114 -2.750798 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -1.385300 -10.054082 0.000000
      vertex -1.031685 -3.715907 0.000000
      vertex -0.621246 -3.854200 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -1.385300 -10.054082 0.000000
      vertex -0.621246 -3.854200 0.000000
      vertex -0.198260 -3.947306 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 0.677891 -11.549590 0.000000
      vertex -1.385300 -10.054082 0.000000
      vertex -0.198260 -3.947306 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 0.677891 -11.549590 0.000000
      vertex -0.198260 -3.947306 0.000000
      vertex 0.232312 -3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 1.434067 -12.024600 0.000000
      vertex 0.677891 -11.549590 0.000000
      vertex 0.232312 -3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 1.434067 -12.024600 0.000000
      vertex 0.232312 -3.994134 0.000000
      vertex 0.665423 -3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 1.095996 -3.947306 0.000000
      vertex 1.434067 -12.024600 0.000000
      vertex 0.665423 -3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 4.425419 -0.432476 0.000000
      vertex 4.448867 -0.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 4.448867 -0.000000 0.000000
      vertex 4.425419 0.432476 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 4.355350 0.859882 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 4.425419 0.432476 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 3.876296 2.062216 0.000000
      vertex 3.633240 2.420697 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 3.633240 2.420697 0.000000
      vertex 3.352849 2.750798 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 3.352849 2.750798 0.000000
      vertex 3.038413 3.048648 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 3.038413 3.048648 0.000000
      vertex 2.693616 3.310756 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -3.333524 7.932395 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 2.693616 3.310756 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -3.333524 7.932395 0.000000
      vertex 2.693616 3.310756 0.000000
      vertex 2.322501 3.534048 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 1.929420 3.715907 0.000000
      vertex -3.333524 7.932395 0.000000
      vertex 2.322501 3.534048 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -3.333524 7.932395 0.000000
      vertex 1.095996 3.947306 0.000000
      vertex 0.665423 3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -3.333524 7.932395 0.000000
      vertex 0.665423 3.994134 0.000000
      vertex 0.232312 3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -5.956253 3.811934 0.000000
      vertex -3.333524 7.932395 0.000000
      vertex 0.232312 3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -5.956253 3.811934 0.000000
      vertex 0.232312 3.994134 0.000000
      vertex -0.198260 3.947306 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex -0.621246 3.854200 0.000000
      vertex -5.956253 3.811934 0.000000
      vertex -0.198260 3.947306 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 4.355350 0.859882 0.000000
      vertex 4.239480 1.277206 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 4.239480 1.277206 0.000000
      vertex 4.079169 1.679556 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 3.876296 2.062216 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 4.079169 1.679556 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 46.274460 -22.422230 0.000000
      vertex 46.020870 -22.900555 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 51.367657 -20.065868 0.000000
      vertex 50.829441 -20.007332 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 2.877826 -12.835510 0.000000
      vertex 45.820480 -23.403492 0.000000
      vertex 45.675644 -23.925148 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 1.434067 -12.024600 0.000000
      vertex 1.929420 -3.715907 0.000000
      vertex 2.322501 -3.534048 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 1.434067 -12.024600 0.000000
      vertex 2.322501 -3.534048 0.000000
      vertex 25.003807 -12.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 2.877826 -12.835510 0.000000
      vertex 1.434067 -12.024600 0.000000
      vertex 25.003807 -12.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 2.877826 -12.835510 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 46.020870 -22.900555 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 45.820480 -23.403492 0.000000
      vertex 2.877826 -12.835510 0.000000
      vertex 46.020870 -22.900555 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 2.877826 -12.835510 0.000000
      vertex 45.675644 -23.925148 0.000000
      vertex 45.588058 -24.459404 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 2.877826 -12.835510 0.000000
      vertex 45.588058 -24.459404 0.000000
      vertex 45.558746 -25.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 45.588058 -25.540596 0.000000
      vertex 2.877826 -12.835510 0.000000
      vertex 45.558746 -25.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 52.900787 -29.417559 0.000000
      vertex 57.194530 -33.828274 0.000000
      vertex 52.409435 -29.644884 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 51.896389 -20.182251 0.000000
      vertex 51.367657 -20.065868 0.000000
      vertex 25.003807 -12.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 51.896389 -20.182251 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 46.875835 0.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 52.409435 -20.355116 0.000000
      vertex 51.896389 -20.182251 0.000000
      vertex 46.875835 0.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 50.829441 -20.007332 0.000000
      vertex 50.288052 -20.007332 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 50.288052 -20.007332 0.000000
      vertex 49.749836 -20.065868 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 49.221107 -20.182251 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 49.749836 -20.065868 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 47.321815 -21.189190 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 47.752811 -20.861555 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 41.827843 -33.105396 0.000000
      vertex 46.274460 -27.577768 0.000000
      vertex 46.578281 -28.025871 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 57.194530 -33.828274 0.000000
      vertex 49.749836 -29.934132 0.000000
      vertex 50.288052 -29.992668 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 57.194530 -33.828274 0.000000
      vertex 50.288052 -29.992668 0.000000
      vertex 50.829441 -29.992668 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 49.221107 -20.182251 0.000000
      vertex 48.708054 -20.355116 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 48.708054 -20.355116 0.000000
      vertex 48.216705 -20.582439 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 47.752811 -20.861555 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 48.216705 -20.582439 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 47.321815 -21.189190 0.000000
      vertex 46.928772 -21.561504 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 46.928772 -21.561504 0.000000
      vertex 46.578281 -21.974129 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 46.274460 -22.422230 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 46.578281 -21.974129 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 2.877826 -12.835510 0.000000
      vertex 45.588058 -25.540596 0.000000
      vertex 45.675644 -26.074852 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 2.877826 -12.835510 0.000000
      vertex 45.675644 -26.074852 0.000000
      vertex 45.820480 -26.596506 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 41.827843 -33.105396 0.000000
      vertex 2.877826 -12.835510 0.000000
      vertex 45.820480 -26.596506 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 41.827843 -33.105396 0.000000
      vertex 45.820480 -26.596506 0.000000
      vertex 46.020870 -27.099445 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 46.274460 -27.577768 0.000000
      vertex 41.827843 -33.105396 0.000000
      vertex 46.020870 -27.099445 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 41.827843 -33.105396 0.000000
      vertex 46.578281 -28.025871 0.000000
      vertex 46.928772 -28.438498 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 41.827843 -33.105396 0.000000
      vertex 46.928772 -28.438498 0.000000
      vertex 47.321815 -28.810810 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 47.752811 -29.138447 0.000000
      vertex 41.827843 -33.105396 0.000000
      vertex 47.321815 -28.810810 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 49.749836 -29.934132 0.000000
      vertex 41.827843 -33.105396 0.000000
      vertex 49.221107 -29.817751 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 54.539211 -21.974129 0.000000
      vertex 54.188725 -21.561504 0.000000
      vertex 61.308319 -19.666462 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 54.539211 -21.974129 0.000000
      vertex 61.308319 -19.666462 0.000000
      vertex 54.843029 -22.422230 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 57.194530 -33.828274 0.000000
      vertex 50.829441 -29.992668 0.000000
      vertex 51.367657 -29.934132 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 57.194530 -33.828274 0.000000
      vertex 51.367657 -29.934132 0.000000
      vertex 51.896389 -29.817751 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 52.409435 -29.644884 0.000000
      vertex 57.194530 -33.828274 0.000000
      vertex 51.896389 -29.817751 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 57.194530 -33.828274 0.000000
      vertex 52.900787 -29.417559 0.000000
      vertex 53.364681 -29.138447 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 57.194530 -33.828274 0.000000
      vertex 53.364681 -29.138447 0.000000
      vertex 53.795677 -28.810810 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 58.211559 -32.987270 0.000000
      vertex 57.194530 -33.828274 0.000000
      vertex 53.795677 -28.810810 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 58.211559 -32.987270 0.000000
      vertex 53.795677 -28.810810 0.000000
      vertex 54.188725 -28.438498 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 59.131466 -32.041012 0.000000
      vertex 58.211559 -32.987270 0.000000
      vertex 54.188725 -28.438498 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 59.131466 -32.041012 0.000000
      vertex 54.188725 -28.438498 0.000000
      vertex 54.539211 -28.025871 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 59.943424 -31.000648 0.000000
      vertex 59.131466 -32.041012 0.000000
      vertex 54.539211 -28.025871 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 59.943424 -31.000648 0.000000
      vertex 54.539211 -28.025871 0.000000
      vertex 54.843029 -27.577768 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 60.637867 -29.878424 0.000000
      vertex 59.943424 -31.000648 0.000000
      vertex 54.843029 -27.577768 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 60.637867 -29.878424 0.000000
      vertex 54.843029 -27.577768 0.000000
      vertex 55.096622 -27.099445 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 61.206615 -28.687559 0.000000
      vertex 60.637867 -29.878424 0.000000
      vertex 55.096622 -27.099445 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.206615 -28.687559 0.000000
      vertex 55.096622 -27.099445 0.000000
      vertex 55.297012 -26.596506 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 61.642979 -27.442078 0.000000
      vertex 61.206615 -28.687559 0.000000
      vertex 55.297012 -26.596506 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.642979 -27.442078 0.000000
      vertex 55.297012 -26.596506 0.000000
      vertex 55.441849 -26.074852 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 61.941811 -26.156645 0.000000
      vertex 61.642979 -27.442078 0.000000
      vertex 55.441849 -26.074852 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.941811 -26.156645 0.000000
      vertex 55.441849 -26.074852 0.000000
      vertex 55.529438 -25.540596 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 62.099590 -24.846401 0.000000
      vertex 61.941811 -26.156645 0.000000
      vertex 55.529438 -25.540596 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 62.099590 -24.846401 0.000000
      vertex 55.529438 -25.540596 0.000000
      vertex 55.558750 -25.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 62.114471 -23.526775 0.000000
      vertex 62.099590 -24.846401 0.000000
      vertex 55.558750 -25.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 62.114471 -23.526775 0.000000
      vertex 55.558750 -25.000000 0.000000
      vertex 55.529438 -24.459404 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 61.986267 -22.213308 0.000000
      vertex 62.114471 -23.526775 0.000000
      vertex 55.529438 -24.459404 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.986267 -22.213308 0.000000
      vertex 55.529438 -24.459404 0.000000
      vertex 55.441849 -23.925148 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 61.716492 -20.921465 0.000000
      vertex 61.986267 -22.213308 0.000000
      vertex 55.441849 -23.925148 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.716492 -20.921465 0.000000
      vertex 55.441849 -23.925148 0.000000
      vertex 55.297012 -23.403492 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 61.308319 -19.666462 0.000000
      vertex 61.716492 -20.921465 0.000000
      vertex 55.297012 -23.403492 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.308319 -19.666462 0.000000
      vertex 55.297012 -23.403492 0.000000
      vertex 55.096622 -22.900555 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 54.843029 -22.422230 0.000000
      vertex 61.308319 -19.666462 0.000000
      vertex 55.096622 -22.900555 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.308319 -19.666462 0.000000
      vertex 54.188725 -21.561504 0.000000
      vertex 53.795677 -21.189190 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 61.308319 -19.666462 0.000000
      vertex 53.795677 -21.189190 0.000000
      vertex 53.364681 -20.861555 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 46.875835 0.000000 0.000000
      vertex 61.308319 -19.666462 0.000000
      vertex 53.364681 -20.861555 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 46.875835 0.000000 0.000000
      vertex 53.364681 -20.861555 0.000000
      vertex 52.900787 -20.582439 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 52.409435 -20.355116 0.000000
      vertex 46.875835 0.000000 0.000000
      vertex 52.900787 -20.582439 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 41.827843 -33.105396 0.000000
      vertex 47.752811 -29.138447 0.000000
      vertex 48.216705 -29.417559 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 41.827843 -33.105396 0.000000
      vertex 48.216705 -29.417559 0.000000
      vertex 48.708054 -29.644884 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 49.221107 -29.817751 0.000000
      vertex 41.827843 -33.105396 0.000000
      vertex 48.708054 -29.644884 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 41.827843 -33.105396 0.000000
      vertex 49.749836 -29.934132 0.000000
      vertex 57.194530 -33.828274 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 41.827843 -33.105396 0.000000
      vertex 57.194530 -33.828274 0.000000
      vertex 56.092358 -34.554123 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 54.918030 -35.156269 0.000000
      vertex 41.827843 -33.105396 0.000000
      vertex 56.092358 -34.554123 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 41.827843 -33.105396 0.000000
      vertex 54.918030 -35.156269 0.000000
      vertex 53.685364 -35.627617 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 41.827843 -33.105396 0.000000
      vertex 53.685364 -35.627617 0.000000
      vertex 52.408882 -35.962624 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 51.103615 -36.157333 0.000000
      vertex 41.827843 -33.105396 0.000000
      vertex 52.408882 -35.962624 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 41.827843 -33.105396 0.000000
      vertex 51.103615 -36.157333 0.000000
      vertex 49.784931 -36.209461 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 41.827843 -33.105396 0.000000
      vertex 49.784931 -36.209461 0.000000
      vertex 48.468369 -36.118393 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 47.169426 -35.885197 0.000000
      vertex 41.827843 -33.105396 0.000000
      vertex 48.468369 -36.118393 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 38.415653 12.852320 0.000000
      vertex 40.776123 8.277181 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 40.776123 8.277181 0.000000
      vertex 43.606743 3.977030 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 46.875835 0.000000 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 43.606743 3.977030 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 30.000000 0.000000
      vertex 34.119015 32.844608 0.000000
      vertex 34.391346 27.703640 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 30.000000 0.000000
      vertex 34.391346 27.703640 0.000000
      vertex 35.205296 22.620216 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 25.003807 30.000000 0.000000
      vertex 35.205296 22.620216 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 -12.000000 0.000000
      vertex 35.205296 22.620216 0.000000
      vertex 36.551758 17.651237 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 38.415653 12.852320 0.000000
      vertex 25.003807 -12.000000 0.000000
      vertex 36.551758 17.651237 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 46.875835 65.689217 0.000000
      vertex 43.606743 61.712185 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 43.606743 61.712185 0.000000
      vertex 40.776123 57.412037 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 38.415653 52.836895 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex 40.776123 57.412037 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 38.415653 52.836895 0.000000
      vertex 36.551758 48.037979 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 72.000000 0.000000
      vertex 36.551758 48.037979 0.000000
      vertex 35.205296 43.068996 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 30.000000 0.000000
      vertex 25.003807 72.000000 0.000000
      vertex 35.205296 43.068996 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 25.003807 30.000000 0.000000
      vertex 35.205296 43.068996 0.000000
      vertex 34.391346 37.985573 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 34.119015 32.844608 0.000000
      vertex 25.003807 30.000000 0.000000
      vertex 34.391346 37.985573 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 2.877826 -12.835510 15.000000
      vertex 25.003807 -24.350040 15.000000
      vertex 25.003807 -12.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 30.000000 15.000000
      vertex 34.119015 32.844608 15.000000
      vertex 34.391346 37.985573 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 38.415653 52.836895 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 36.551758 48.037979 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 25.003807 30.000000 15.000000
      vertex 34.391346 37.985573 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 34.391346 37.985573 15.000000
      vertex 35.205296 43.068996 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 36.551758 48.037979 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 35.205296 43.068996 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 38.415653 52.836895 15.000000
      vertex 40.776123 57.412037 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 40.776123 57.412037 15.000000
      vertex 43.606743 61.712185 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 65.689217 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 43.606743 61.712185 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 30.000000 15.000000
      vertex 36.551758 17.651237 15.000000
      vertex 35.205296 22.620216 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 30.000000 15.000000
      vertex 35.205296 22.620216 15.000000
      vertex 34.391346 27.703640 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 34.119015 32.844608 15.000000
      vertex 25.003807 30.000000 15.000000
      vertex 34.391346 27.703640 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 46.875835 0.000000 15.000000
      vertex 43.606743 3.977030 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 43.606743 3.977030 15.000000
      vertex 40.776123 8.277181 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 38.415653 12.852320 15.000000
      vertex 25.003807 -12.000000 15.000000
      vertex 40.776123 8.277181 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 46.274460 -22.422230 15.000000
      vertex 46.578281 -21.974129 15.000000
      vertex 25.003807 -12.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.274460 -22.422230 15.000000
      vertex 25.003807 -12.000000 15.000000
      vertex 46.020870 -22.900555 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 45.588058 -25.540596 15.000000
      vertex 45.558746 -25.000000 15.000000
      vertex 25.003807 -24.350040 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 45.588058 -25.540596 15.000000
      vertex 25.003807 -24.350040 15.000000
      vertex 45.675644 -26.074852 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -24.350040 15.000000
      vertex 45.558746 -25.000000 15.000000
      vertex 45.588058 -24.459404 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -24.350040 15.000000
      vertex 45.588058 -24.459404 15.000000
      vertex 45.675644 -23.925148 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 25.003807 -24.350040 15.000000
      vertex 45.675644 -23.925148 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 45.675644 -23.925148 15.000000
      vertex 45.820480 -23.403492 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.020870 -22.900555 15.000000
      vertex 25.003807 -12.000000 15.000000
      vertex 45.820480 -23.403492 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 50.288052 -20.007332 15.000000
      vertex 46.875835 0.000000 15.000000
      vertex 49.749836 -20.065868 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 0.000000 15.000000
      vertex 51.896389 -20.182251 15.000000
      vertex 52.409435 -20.355116 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 0.000000 15.000000
      vertex 52.409435 -20.355116 15.000000
      vertex 52.900787 -20.582439 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.308319 -19.666462 15.000000
      vertex 46.875835 0.000000 15.000000
      vertex 52.900787 -20.582439 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 46.578281 -21.974129 15.000000
      vertex 46.928772 -21.561504 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 46.928772 -21.561504 15.000000
      vertex 47.321815 -21.189190 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 0.000000 15.000000
      vertex 25.003807 -12.000000 15.000000
      vertex 47.321815 -21.189190 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 0.000000 15.000000
      vertex 47.321815 -21.189190 15.000000
      vertex 47.752811 -20.861555 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 48.216705 -20.582439 15.000000
      vertex 46.875835 0.000000 15.000000
      vertex 47.752811 -20.861555 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 0.000000 15.000000
      vertex 48.216705 -20.582439 15.000000
      vertex 48.708054 -20.355116 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 0.000000 15.000000
      vertex 48.708054 -20.355116 15.000000
      vertex 49.221107 -20.182251 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 49.749836 -20.065868 15.000000
      vertex 46.875835 0.000000 15.000000
      vertex 49.221107 -20.182251 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 0.000000 15.000000
      vertex 50.288052 -20.007332 15.000000
      vertex 50.829441 -20.007332 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 0.000000 15.000000
      vertex 50.829441 -20.007332 15.000000
      vertex 51.367657 -20.065868 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 51.896389 -20.182251 15.000000
      vertex 46.875835 0.000000 15.000000
      vertex 51.367657 -20.065868 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.716492 -20.921465 15.000000
      vertex 61.308319 -19.666462 15.000000
      vertex 55.096622 -22.900555 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.716492 -20.921465 15.000000
      vertex 55.096622 -22.900555 15.000000
      vertex 55.297012 -23.403492 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.986267 -22.213308 15.000000
      vertex 61.716492 -20.921465 15.000000
      vertex 55.297012 -23.403492 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.986267 -22.213308 15.000000
      vertex 55.297012 -23.403492 15.000000
      vertex 55.441849 -23.925148 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 62.114471 -23.526775 15.000000
      vertex 61.986267 -22.213308 15.000000
      vertex 55.441849 -23.925148 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 62.114471 -23.526775 15.000000
      vertex 55.441849 -23.925148 15.000000
      vertex 55.529438 -24.459404 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 62.099590 -24.846401 15.000000
      vertex 62.114471 -23.526775 15.000000
      vertex 55.529438 -24.459404 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 62.099590 -24.846401 15.000000
      vertex 55.529438 -24.459404 15.000000
      vertex 55.558750 -25.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 61.941811 -26.156645 15.000000
      vertex 62.099590 -24.846401 15.000000
      vertex 55.558750 -25.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.941811 -26.156645 15.000000
      vertex 55.558750 -25.000000 15.000000
      vertex 55.529438 -25.540596 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 61.642979 -27.442078 15.000000
      vertex 61.941811 -26.156645 15.000000
      vertex 55.529438 -25.540596 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.642979 -27.442078 15.000000
      vertex 55.529438 -25.540596 15.000000
      vertex 55.441849 -26.074852 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 61.206615 -28.687559 15.000000
      vertex 61.642979 -27.442078 15.000000
      vertex 55.441849 -26.074852 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.206615 -28.687559 15.000000
      vertex 55.441849 -26.074852 15.000000
      vertex 55.297012 -26.596506 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 60.637867 -29.878424 15.000000
      vertex 61.206615 -28.687559 15.000000
      vertex 55.297012 -26.596506 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 60.637867 -29.878424 15.000000
      vertex 55.297012 -26.596506 15.000000
      vertex 55.096622 -27.099445 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 59.943424 -31.000648 15.000000
      vertex 60.637867 -29.878424 15.000000
      vertex 55.096622 -27.099445 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 59.943424 -31.000648 15.000000
      vertex 55.096622 -27.099445 15.000000
      vertex 54.843029 -27.577768 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 59.131466 -32.041012 15.000000
      vertex 59.943424 -31.000648 15.000000
      vertex 54.843029 -27.577768 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 59.131466 -32.041012 15.000000
      vertex 54.843029 -27.577768 15.000000
      vertex 54.539211 -28.025871 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 58.211559 -32.987270 15.000000
      vertex 59.131466 -32.041012 15.000000
      vertex 54.539211 -28.025871 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 58.211559 -32.987270 15.000000
      vertex 54.539211 -28.025871 15.000000
      vertex 54.188725 -28.438498 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 57.194530 -33.828274 15.000000
      vertex 58.211559 -32.987270 15.000000
      vertex 54.188725 -28.438498 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 57.194530 -33.828274 15.000000
      vertex 54.188725 -28.438498 15.000000
      vertex 53.795677 -28.810810 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 53.364681 -29.138447 15.000000
      vertex 57.194530 -33.828274 15.000000
      vertex 53.795677 -28.810810 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 47.321815 -28.810810 15.000000
      vertex 46.928772 -28.438498 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 46.928772 -28.438498 15.000000
      vertex 46.578281 -28.025871 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.308319 -19.666462 15.000000
      vertex 52.900787 -20.582439 15.000000
      vertex 53.364681 -20.861555 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.308319 -19.666462 15.000000
      vertex 53.364681 -20.861555 15.000000
      vertex 53.795677 -21.189190 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 54.188725 -21.561504 15.000000
      vertex 61.308319 -19.666462 15.000000
      vertex 53.795677 -21.189190 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 57.194530 -33.828274 15.000000
      vertex 53.364681 -29.138447 15.000000
      vertex 52.900787 -29.417559 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 57.194530 -33.828274 15.000000
      vertex 52.900787 -29.417559 15.000000
      vertex 52.409435 -29.644884 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 51.896389 -29.817751 15.000000
      vertex 57.194530 -33.828274 15.000000
      vertex 52.409435 -29.644884 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 56.092358 -34.554123 15.000000
      vertex 57.194530 -33.828274 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 57.194530 -33.828274 15.000000
      vertex 50.288052 -29.992668 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 46.578281 -28.025871 15.000000
      vertex 46.274460 -27.577768 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 46.274460 -27.577768 15.000000
      vertex 46.020870 -27.099445 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -24.350040 15.000000
      vertex 41.827843 -33.105396 15.000000
      vertex 46.020870 -27.099445 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -24.350040 15.000000
      vertex 46.020870 -27.099445 15.000000
      vertex 45.820480 -26.596506 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 45.675644 -26.074852 15.000000
      vertex 25.003807 -24.350040 15.000000
      vertex 45.820480 -26.596506 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.308319 -19.666462 15.000000
      vertex 54.188725 -21.561504 15.000000
      vertex 54.539211 -21.974129 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.308319 -19.666462 15.000000
      vertex 54.539211 -21.974129 15.000000
      vertex 54.843029 -22.422230 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 55.096622 -22.900555 15.000000
      vertex 61.308319 -19.666462 15.000000
      vertex 54.843029 -22.422230 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 57.194530 -33.828274 15.000000
      vertex 51.896389 -29.817751 15.000000
      vertex 51.367657 -29.934132 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 57.194530 -33.828274 15.000000
      vertex 51.367657 -29.934132 15.000000
      vertex 50.829441 -29.992668 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 50.288052 -29.992668 15.000000
      vertex 57.194530 -33.828274 15.000000
      vertex 50.829441 -29.992668 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 50.288052 -29.992668 15.000000
      vertex 49.749836 -29.934132 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 49.749836 -29.934132 15.000000
      vertex 49.221107 -29.817751 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 48.708054 -29.644884 15.000000
      vertex 41.827843 -33.105396 15.000000
      vertex 49.221107 -29.817751 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 48.708054 -29.644884 15.000000
      vertex 48.216705 -29.417559 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 48.216705 -29.417559 15.000000
      vertex 47.752811 -29.138447 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 47.321815 -28.810810 15.000000
      vertex 41.827843 -33.105396 15.000000
      vertex 47.752811 -29.138447 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 48.468369 -36.118393 15.000000
      vertex 41.827843 -33.105396 15.000000
      vertex 47.169426 -35.885197 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 48.468369 -36.118393 15.000000
      vertex 49.784931 -36.209461 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 49.784931 -36.209461 15.000000
      vertex 51.103615 -36.157333 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 52.408882 -35.962624 15.000000
      vertex 41.827843 -33.105396 15.000000
      vertex 51.103615 -36.157333 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 52.408882 -35.962624 15.000000
      vertex 53.685364 -35.627617 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 53.685364 -35.627617 15.000000
      vertex 54.918030 -35.156269 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 56.092358 -34.554123 15.000000
      vertex 41.827843 -33.105396 15.000000
      vertex 54.918030 -35.156269 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 4.425419 0.432476 15.000000
      vertex 4.448867 -0.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 2.877826 -12.835510 15.000000
      vertex 2.322501 -3.534048 15.000000
      vertex 1.929420 -3.715907 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 30.000000 15.000000
      vertex 2.428029 31.369322 15.000000
      vertex 2.448868 29.998724 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 30.000000 15.000000
      vertex 2.448868 29.998724 15.000000
      vertex 2.311483 26.486357 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 30.000000 15.000000
      vertex 2.311483 26.486357 15.000000
      vertex 1.666403 21.644791 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 30.000000 15.000000
      vertex 1.666403 21.644791 15.000000
      vertex 25.003807 -12.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 36.551758 17.651237 15.000000
      vertex 25.003807 30.000000 15.000000
      vertex 25.003807 -12.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 36.551758 17.651237 15.000000
      vertex 25.003807 -12.000000 15.000000
      vertex 38.415653 12.852320 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 1.666403 21.644791 15.000000
      vertex 0.500388 16.901657 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 0.500388 16.901657 15.000000
      vertex -1.172825 12.312838 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -3.333524 7.932395 15.000000
      vertex 25.003807 -12.000000 15.000000
      vertex -1.172825 12.312838 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.181434 -1.679556 15.000000
      vertex -7.896352 -2.291907 15.000000
      vertex -6.563149 -4.463514 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.181434 -1.679556 15.000000
      vertex -6.563149 -4.463514 15.000000
      vertex -2.978561 -2.062216 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.333524 7.932395 15.000000
      vertex 1.518981 3.854200 15.000000
      vertex 1.929420 3.715907 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 4.448867 -0.000000 15.000000
      vertex 4.425419 -0.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 4.425419 -0.432476 15.000000
      vertex 4.355350 -0.859882 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 4.239480 -1.277206 15.000000
      vertex 25.003807 -12.000000 15.000000
      vertex 4.355350 -0.859882 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 4.239480 -1.277206 15.000000
      vertex 4.079169 -1.679556 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 4.079169 -1.679556 15.000000
      vertex 3.876296 -2.062216 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 3.633240 -2.420697 15.000000
      vertex 25.003807 -12.000000 15.000000
      vertex 3.876296 -2.062216 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 3.633240 -2.420697 15.000000
      vertex 3.352849 -2.750798 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 3.352849 -2.750798 15.000000
      vertex 3.038413 -3.048648 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 2.877826 -12.835510 15.000000
      vertex 25.003807 -12.000000 15.000000
      vertex 3.038413 -3.048648 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 2.877826 -12.835510 15.000000
      vertex 3.038413 -3.048648 15.000000
      vertex 2.693616 -3.310756 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 2.322501 -3.534048 15.000000
      vertex 2.877826 -12.835510 15.000000
      vertex 2.693616 -3.310756 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -0.621246 -3.854200 15.000000
      vertex -3.291848 -8.363408 15.000000
      vertex -1.385300 -10.054082 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -1.424766 -3.534048 15.000000
      vertex -1.795881 -3.310756 15.000000
      vertex -5.023365 -6.493875 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -1.424766 -3.534048 15.000000
      vertex -5.023365 -6.493875 15.000000
      vertex -3.291848 -8.363408 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -1.031685 -3.715907 15.000000
      vertex -1.424766 -3.534048 15.000000
      vertex -3.291848 -8.363408 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -1.031685 -3.715907 15.000000
      vertex -3.291848 -8.363408 15.000000
      vertex -0.621246 -3.854200 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -5.023365 -6.493875 15.000000
      vertex -1.795881 -3.310756 15.000000
      vertex -2.140677 -3.048648 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -5.023365 -6.493875 15.000000
      vertex -2.140677 -3.048648 15.000000
      vertex -2.455114 -2.750798 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -6.563149 -4.463514 15.000000
      vertex -5.023365 -6.493875 15.000000
      vertex -2.455114 -2.750798 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -6.563149 -4.463514 15.000000
      vertex -2.455114 -2.750798 15.000000
      vertex -2.735505 -2.420697 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -2.978561 -2.062216 15.000000
      vertex -6.563149 -4.463514 15.000000
      vertex -2.735505 -2.420697 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -7.896352 -2.291907 15.000000
      vertex -5.956253 3.811934 15.000000
      vertex -9.010113 0.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 2.877826 -12.835510 15.000000
      vertex 1.929420 -3.715907 15.000000
      vertex 1.518981 -3.854200 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 2.877826 -12.835510 15.000000
      vertex 1.518981 -3.854200 15.000000
      vertex 1.095996 -3.947306 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 0.677891 -11.549590 15.000000
      vertex 2.877826 -12.835510 15.000000
      vertex 1.095996 -3.947306 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 0.677891 -11.549590 15.000000
      vertex 1.095996 -3.947306 15.000000
      vertex 0.665423 -3.994134 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.677891 -11.549590 15.000000
      vertex 0.665423 -3.994134 15.000000
      vertex 0.232312 -3.994134 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -1.385300 -10.054082 15.000000
      vertex 0.677891 -11.549590 15.000000
      vertex 0.232312 -3.994134 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -1.385300 -10.054082 15.000000
      vertex 0.232312 -3.994134 15.000000
      vertex -0.198260 -3.947306 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -0.621246 -3.854200 15.000000
      vertex -1.385300 -10.054082 15.000000
      vertex -0.198260 -3.947306 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -2.455114 2.750798 15.000000
      vertex -2.140677 3.048648 15.000000
      vertex -3.333524 7.932395 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -2.455114 2.750798 15.000000
      vertex -3.333524 7.932395 15.000000
      vertex -5.956253 3.811934 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.333524 7.932395 15.000000
      vertex -2.140677 3.048648 15.000000
      vertex -1.795881 3.310756 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.333524 7.932395 15.000000
      vertex -1.795881 3.310756 15.000000
      vertex -1.424766 3.534048 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -1.031685 3.715907 15.000000
      vertex -3.333524 7.932395 15.000000
      vertex -1.424766 3.534048 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -5.956253 3.811934 15.000000
      vertex -7.896352 -2.291907 15.000000
      vertex -3.181434 -1.679556 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -5.956253 3.811934 15.000000
      vertex -3.181434 -1.679556 15.000000
      vertex -3.341745 -1.277206 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.457615 -0.859882 15.000000
      vertex -5.956253 3.811934 15.000000
      vertex -3.341745 -1.277206 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -5.956253 3.811934 15.000000
      vertex -3.181434 1.679556 15.000000
      vertex -2.978561 2.062216 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -5.956253 3.811934 15.000000
      vertex -2.978561 2.062216 15.000000
      vertex -2.735505 2.420697 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -2.455114 2.750798 15.000000
      vertex -5.956253 3.811934 15.000000
      vertex -2.735505 2.420697 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 3.352849 2.750798 15.000000
      vertex 3.633240 2.420697 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 3.633240 2.420697 15.000000
      vertex 3.876296 2.062216 15.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 4.079169 1.679556 15.000000
      vertex 25.003807 -12.000000 15.000000
      vertex 3.876296 2.062216 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -5.956253 3.811934 15.000000
      vertex -3.457615 -0.859882 15.000000
      vertex -3.527684 -0.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -5.956253 3.811934 15.000000
      vertex -3.527684 -0.432476 15.000000
      vertex -3.551132 -0.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.527684 0.432476 15.000000
      vertex -5.956253 3.811934 15.000000
      vertex -3.551132 -0.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -5.956253 3.811934 15.000000
      vertex -3.527684 0.432476 15.000000
      vertex -3.457615 0.859882 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -5.956253 3.811934 15.000000
      vertex -3.457615 0.859882 15.000000
      vertex -3.341745 1.277206 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.181434 1.679556 15.000000
      vertex -5.956253 3.811934 15.000000
      vertex -3.341745 1.277206 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.333524 7.932395 15.000000
      vertex -1.031685 3.715907 15.000000
      vertex -0.621246 3.854200 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.333524 7.932395 15.000000
      vertex -0.621246 3.854200 15.000000
      vertex -0.198260 3.947306 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.232312 3.994134 15.000000
      vertex -3.333524 7.932395 15.000000
      vertex -0.198260 3.947306 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.333524 7.932395 15.000000
      vertex 1.929420 3.715907 15.000000
      vertex 2.322501 3.534048 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.333524 7.932395 15.000000
      vertex 2.322501 3.534048 15.000000
      vertex 2.693616 3.310756 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex -3.333524 7.932395 15.000000
      vertex 2.693616 3.310756 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 2.693616 3.310756 15.000000
      vertex 3.038413 3.048648 15.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 3.352849 2.750798 15.000000
      vertex 25.003807 -12.000000 15.000000
      vertex 3.038413 3.048648 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 4.079169 1.679556 15.000000
      vertex 4.239480 1.277206 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 -12.000000 15.000000
      vertex 4.239480 1.277206 15.000000
      vertex 4.355350 0.859882 15.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 4.425419 0.432476 15.000000
      vertex 25.003807 -12.000000 15.000000
      vertex 4.355350 0.859882 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.333524 7.932395 15.000000
      vertex 0.232312 3.994134 15.000000
      vertex 0.665423 3.994134 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.333524 7.932395 15.000000
      vertex 0.665423 3.994134 15.000000
      vertex 1.095996 3.947306 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 1.518981 3.854200 15.000000
      vertex -3.333524 7.932395 15.000000
      vertex 1.095996 3.947306 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 0.232329 63.994133 15.000000
      vertex -27.297455 72.335861 15.000000
      vertex -0.198244 63.947304 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -22.798897 70.433266 15.000000
      vertex -18.533041 68.054321 15.000000
      vertex -3.551116 60.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -22.798897 70.433266 15.000000
      vertex -3.551116 60.000000 15.000000
      vertex -3.527667 60.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 0.232329 63.994133 15.000000
      vertex 0.665440 63.994133 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 0.665440 63.994133 15.000000
      vertex 1.096012 63.947304 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 1.518998 63.854202 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 1.096012 63.947304 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -4.748533 54.412365 15.000000
      vertex -0.621229 56.145798 15.000000
      vertex -7.617054 58.365650 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex -2.325371 50.171467 15.000000
      vertex -0.376117 45.692932 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex -0.376117 45.692932 15.000000
      vertex 1.076266 41.029510 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 25.003807 30.000000 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 1.076266 41.029510 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 30.000000 15.000000
      vertex 1.076266 41.029510 15.000000
      vertex 2.014667 36.236149 15.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 2.428029 31.369322 15.000000
      vertex 25.003807 30.000000 15.000000
      vertex 2.014667 36.236149 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -27.297455 72.335861 15.000000
      vertex -2.140661 63.048645 15.000000
      vertex -1.795864 63.310757 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -27.297455 72.335861 15.000000
      vertex -1.795864 63.310757 15.000000
      vertex -1.424749 63.534050 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -22.798897 70.433266 15.000000
      vertex -3.527667 60.432476 15.000000
      vertex -3.457598 60.859882 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -22.798897 70.433266 15.000000
      vertex -3.457598 60.859882 15.000000
      vertex -3.341728 61.277206 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.181417 61.679558 15.000000
      vertex -22.798897 70.433266 15.000000
      vertex -3.341728 61.277206 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -27.297455 72.335861 15.000000
      vertex -1.424749 63.534050 15.000000
      vertex -1.031668 63.715904 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -27.297455 72.335861 15.000000
      vertex -1.031668 63.715904 15.000000
      vertex -0.621229 63.854202 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -0.198244 63.947304 15.000000
      vertex -27.297455 72.335861 15.000000
      vertex -0.621229 63.854202 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -7.617054 58.365650 15.000000
      vertex -0.621229 56.145798 15.000000
      vertex -1.031668 56.284092 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -7.617054 58.365650 15.000000
      vertex -1.031668 56.284092 15.000000
      vertex -1.424749 56.465954 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -1.795864 56.689243 15.000000
      vertex -7.617054 58.365650 15.000000
      vertex -1.424749 56.465954 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 1.518998 63.854202 15.000000
      vertex 1.929437 63.715904 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 1.929437 63.715904 15.000000
      vertex 2.322518 63.534050 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 2.693633 63.310757 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 2.322518 63.534050 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 2.693633 63.310757 15.000000
      vertex 3.038430 63.048645 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 3.038430 63.048645 15.000000
      vertex 3.352866 62.750801 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 3.633257 62.420696 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 3.352866 62.750801 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -7.617054 58.365650 15.000000
      vertex -1.795864 56.689243 15.000000
      vertex -2.140661 56.951351 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -7.617054 58.365650 15.000000
      vertex -2.140661 56.951351 15.000000
      vertex -2.455098 57.249203 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -2.735488 57.579300 15.000000
      vertex -7.617054 58.365650 15.000000
      vertex -2.455098 57.249203 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -7.617054 58.365650 15.000000
      vertex -2.735488 57.579300 15.000000
      vertex -2.978544 57.937786 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -7.617054 58.365650 15.000000
      vertex -2.978544 57.937786 15.000000
      vertex -3.181417 58.320442 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.341728 58.722794 15.000000
      vertex -7.617054 58.365650 15.000000
      vertex -3.181417 58.320442 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -4.748533 54.412365 15.000000
      vertex 0.665440 56.005867 15.000000
      vertex 0.232329 56.005867 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -4.748533 54.412365 15.000000
      vertex 0.232329 56.005867 15.000000
      vertex -0.198244 56.052692 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -0.621229 56.145798 15.000000
      vertex -4.748533 54.412365 15.000000
      vertex -0.198244 56.052692 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 4.448884 60.000000 15.000000
      vertex 4.425436 59.567524 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 4.425436 59.567524 15.000000
      vertex 4.355367 59.140121 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 4.239497 58.722794 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 4.355367 59.140121 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -22.798897 70.433266 15.000000
      vertex -3.181417 61.679558 15.000000
      vertex -2.978544 62.062214 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -22.798897 70.433266 15.000000
      vertex -2.978544 62.062214 15.000000
      vertex -2.735488 62.420696 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -27.297455 72.335861 15.000000
      vertex -22.798897 70.433266 15.000000
      vertex -2.735488 62.420696 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -27.297455 72.335861 15.000000
      vertex -2.735488 62.420696 15.000000
      vertex -2.455098 62.750801 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -2.140661 63.048645 15.000000
      vertex -27.297455 72.335861 15.000000
      vertex -2.455098 62.750801 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 3.633257 62.420696 15.000000
      vertex 3.876313 62.062214 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 3.876313 62.062214 15.000000
      vertex 4.079186 61.679558 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 4.239497 61.277206 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 4.079186 61.679558 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 4.239497 61.277206 15.000000
      vertex 4.355367 60.859882 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 4.355367 60.859882 15.000000
      vertex 4.425436 60.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 4.448884 60.000000 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 4.425436 60.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.551116 60.000000 15.000000
      vertex -18.533041 68.054321 15.000000
      vertex -14.550149 65.227043 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.551116 60.000000 15.000000
      vertex -14.550149 65.227043 15.000000
      vertex -10.897141 61.984760 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.527667 59.567524 15.000000
      vertex -3.551116 60.000000 15.000000
      vertex -10.897141 61.984760 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.527667 59.567524 15.000000
      vertex -10.897141 61.984760 15.000000
      vertex -7.617054 58.365650 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.457598 59.140121 15.000000
      vertex -3.527667 59.567524 15.000000
      vertex -7.617054 58.365650 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -3.457598 59.140121 15.000000
      vertex -7.617054 58.365650 15.000000
      vertex -3.341728 58.722794 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -2.325371 50.171467 15.000000
      vertex 2.322518 56.465954 15.000000
      vertex 1.929437 56.284092 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -2.325371 50.171467 15.000000
      vertex 1.929437 56.284092 15.000000
      vertex 1.518998 56.145798 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -4.748533 54.412365 15.000000
      vertex -2.325371 50.171467 15.000000
      vertex 1.518998 56.145798 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -4.748533 54.412365 15.000000
      vertex 1.518998 56.145798 15.000000
      vertex 1.096012 56.052692 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 0.665440 56.005867 15.000000
      vertex -4.748533 54.412365 15.000000
      vertex 1.096012 56.052692 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 4.239497 58.722794 15.000000
      vertex 4.079186 58.320442 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 4.079186 58.320442 15.000000
      vertex 3.876313 57.937786 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 3.633257 57.579300 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 3.876313 57.937786 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 3.633257 57.579300 15.000000
      vertex 3.352866 57.249203 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 3.352866 57.249203 15.000000
      vertex 3.038430 56.951351 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -2.325371 50.171467 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 3.038430 56.951351 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -2.325371 50.171467 15.000000
      vertex 3.038430 56.951351 15.000000
      vertex 2.693633 56.689243 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 2.322518 56.465954 15.000000
      vertex -2.325371 50.171467 15.000000
      vertex 2.693633 56.689243 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -27.297455 72.335861 15.000000
      vertex 0.232329 63.994133 15.000000
      vertex 25.003807 72.000000 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -27.297455 72.335861 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 25.003807 94.112053 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -31.975719 73.739693 15.000000
      vertex -27.297455 72.335861 15.000000
      vertex 25.003807 94.112053 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -84.934654 81.375298 15.000000
      vertex -51.365528 74.128296 15.000000
      vertex -46.530926 74.823669 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -84.934654 81.375298 15.000000
      vertex -46.530926 74.823669 15.000000
      vertex -41.649437 74.990967 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 94.112053 15.000000
      vertex -84.934654 81.375298 15.000000
      vertex -41.649437 74.990967 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 94.112053 15.000000
      vertex -41.649437 74.990967 15.000000
      vertex -36.778576 74.628212 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -31.975719 73.739693 15.000000
      vertex 25.003807 94.112053 15.000000
      vertex -36.778576 74.628212 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -56.096283 72.913033 15.000000
      vertex -51.365528 74.128296 15.000000
      vertex -84.934654 81.375298 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -56.096283 72.913033 15.000000
      vertex -84.934654 81.375298 15.000000
      vertex -87.038231 80.379112 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -89.022804 79.163017 15.000000
      vertex -56.096283 72.913033 15.000000
      vertex -87.038231 80.379112 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -56.096283 72.913033 15.000000
      vertex -89.022804 79.163017 15.000000
      vertex -90.865486 77.741058 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -56.096283 72.913033 15.000000
      vertex -90.865486 77.741058 15.000000
      vertex -92.544991 76.129631 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -56.096283 72.913033 15.000000
      vertex -92.544991 76.129631 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -72.898163 63.227364 15.000000
      vertex -69.118179 66.320679 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -69.118179 66.320679 15.000000
      vertex -65.025208 68.986099 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -65.025208 68.986099 15.000000
      vertex -60.667461 71.192215 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -56.096283 72.913033 15.000000
      vertex -93.972061 72.000000 15.000000
      vertex -60.667461 71.192215 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -81.936371 51.767002 15.000000
      vertex -83.306366 56.689243 15.000000
      vertex -83.677475 56.465954 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -81.936371 51.767002 15.000000
      vertex -83.677475 56.465954 15.000000
      vertex -84.070564 56.284092 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -84.481003 56.145798 15.000000
      vertex -81.936371 51.767002 15.000000
      vertex -84.070564 56.284092 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -81.936371 51.767002 15.000000
      vertex -87.031670 56.284092 15.000000
      vertex -87.424751 56.465954 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -76.320625 59.742584 15.000000
      vertex -81.574570 59.567524 15.000000
      vertex -81.644630 59.140121 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -76.320625 59.742584 15.000000
      vertex -81.644630 59.140121 15.000000
      vertex -81.760506 58.722794 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -79.345238 55.907406 15.000000
      vertex -76.320625 59.742584 15.000000
      vertex -81.760506 58.722794 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -79.345238 55.907406 15.000000
      vertex -81.760506 58.722794 15.000000
      vertex -81.920815 58.320442 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -82.123688 57.937786 15.000000
      vertex -79.345238 55.907406 15.000000
      vertex -81.920815 58.320442 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -86.831276 38.016766 15.000000
      vertex -85.701576 42.768681 15.000000
      vertex -93.972061 72.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -86.831276 38.016766 15.000000
      vertex -93.972061 72.000000 15.000000
      vertex -93.972061 30.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -87.439316 33.170410 15.000000
      vertex -86.831276 38.016766 15.000000
      vertex -93.972061 30.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -81.936371 51.767002 15.000000
      vertex -84.481003 56.145798 15.000000
      vertex -84.903984 56.052692 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -81.936371 51.767002 15.000000
      vertex -84.903984 56.052692 15.000000
      vertex -85.334564 56.005867 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -85.767670 56.005867 15.000000
      vertex -81.936371 51.767002 15.000000
      vertex -85.334564 56.005867 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -81.936371 51.767002 15.000000
      vertex -87.424751 56.465954 15.000000
      vertex -87.795860 56.689243 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -81.936371 51.767002 15.000000
      vertex -87.795860 56.689243 15.000000
      vertex -88.140656 56.951351 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -84.063507 47.370163 15.000000
      vertex -81.936371 51.767002 15.000000
      vertex -88.140656 56.951351 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -84.063507 47.370163 15.000000
      vertex -88.140656 56.951351 15.000000
      vertex -88.455093 57.249203 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -88.735489 57.579300 15.000000
      vertex -84.063507 47.370163 15.000000
      vertex -88.455093 57.249203 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -79.345238 55.907406 15.000000
      vertex -82.123688 57.937786 15.000000
      vertex -82.366745 57.579300 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -79.345238 55.907406 15.000000
      vertex -82.366745 57.579300 15.000000
      vertex -82.647133 57.249203 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -81.936371 51.767002 15.000000
      vertex -79.345238 55.907406 15.000000
      vertex -82.647133 57.249203 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -81.936371 51.767002 15.000000
      vertex -82.647133 57.249203 15.000000
      vertex -82.961563 56.951351 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -83.306366 56.689243 15.000000
      vertex -81.936371 51.767002 15.000000
      vertex -82.961563 56.951351 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -81.936371 51.767002 15.000000
      vertex -85.767670 56.005867 15.000000
      vertex -86.198242 56.052692 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -81.936371 51.767002 15.000000
      vertex -86.198242 56.052692 15.000000
      vertex -86.621231 56.145798 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -87.031670 56.284092 15.000000
      vertex -81.936371 51.767002 15.000000
      vertex -86.621231 56.145798 15.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex -85.334564 63.994133 15.000000
      vertex -84.903984 63.947304 15.000000
      vertex -93.972061 72.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -85.334564 63.994133 15.000000
      vertex -93.972061 72.000000 15.000000
      vertex -85.767670 63.994133 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -84.063507 47.370163 15.000000
      vertex -88.735489 57.579300 15.000000
      vertex -88.978546 57.937786 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -84.063507 47.370163 15.000000
      vertex -88.978546 57.937786 15.000000
      vertex -89.181419 58.320442 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -85.701576 42.768681 15.000000
      vertex -84.063507 47.370163 15.000000
      vertex -89.181419 58.320442 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -85.701576 42.768681 15.000000
      vertex -89.181419 58.320442 15.000000
      vertex -89.341728 58.722794 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -85.701576 42.768681 15.000000
      vertex -89.341728 58.722794 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -89.341728 58.722794 15.000000
      vertex -89.457603 59.140121 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -89.527664 59.567524 15.000000
      vertex -93.972061 72.000000 15.000000
      vertex -89.457603 59.140121 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -89.527664 59.567524 15.000000
      vertex -89.551117 60.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -89.551117 60.000000 15.000000
      vertex -89.527664 60.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -89.457603 60.859882 15.000000
      vertex -93.972061 72.000000 15.000000
      vertex -89.527664 60.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -89.457603 60.859882 15.000000
      vertex -89.341728 61.277206 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -89.341728 61.277206 15.000000
      vertex -89.181419 61.679558 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -88.978546 62.062214 15.000000
      vertex -93.972061 72.000000 15.000000
      vertex -89.181419 61.679558 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -88.978546 62.062214 15.000000
      vertex -88.735489 62.420696 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -88.735489 62.420696 15.000000
      vertex -88.455093 62.750801 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -88.140656 63.048645 15.000000
      vertex -93.972061 72.000000 15.000000
      vertex -88.455093 62.750801 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -88.140656 63.048645 15.000000
      vertex -87.795860 63.310757 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -87.795860 63.310757 15.000000
      vertex -87.424751 63.534050 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -87.031670 63.715904 15.000000
      vertex -93.972061 72.000000 15.000000
      vertex -87.424751 63.534050 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -87.031670 63.715904 15.000000
      vertex -86.621231 63.854202 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -86.621231 63.854202 15.000000
      vertex -86.198242 63.947304 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -85.767670 63.994133 15.000000
      vertex -93.972061 72.000000 15.000000
      vertex -86.198242 63.947304 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -72.898163 63.227364 15.000000
      vertex -83.306366 63.310757 15.000000
      vertex -82.961563 63.048645 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -72.898163 63.227364 15.000000
      vertex -82.961563 63.048645 15.000000
      vertex -82.647133 62.750801 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -82.366745 62.420696 15.000000
      vertex -72.898163 63.227364 15.000000
      vertex -82.647133 62.750801 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -72.898163 63.227364 15.000000
      vertex -82.366745 62.420696 15.000000
      vertex -82.123688 62.062214 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -72.898163 63.227364 15.000000
      vertex -82.123688 62.062214 15.000000
      vertex -81.920815 61.679558 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -81.760506 61.277206 15.000000
      vertex -72.898163 63.227364 15.000000
      vertex -81.920815 61.679558 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -72.898163 63.227364 15.000000
      vertex -81.760506 61.277206 15.000000
      vertex -81.644630 60.859882 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -72.898163 63.227364 15.000000
      vertex -81.644630 60.859882 15.000000
      vertex -81.574570 60.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -76.320625 59.742584 15.000000
      vertex -72.898163 63.227364 15.000000
      vertex -81.574570 60.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -76.320625 59.742584 15.000000
      vertex -81.574570 60.432476 15.000000
      vertex -81.551109 60.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -81.574570 59.567524 15.000000
      vertex -76.320625 59.742584 15.000000
      vertex -81.551109 60.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -84.903984 63.947304 15.000000
      vertex -84.481003 63.854202 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -84.481003 63.854202 15.000000
      vertex -84.070564 63.715904 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -72.898163 63.227364 15.000000
      vertex -93.972061 72.000000 15.000000
      vertex -84.070564 63.715904 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -72.898163 63.227364 15.000000
      vertex -84.070564 63.715904 15.000000
      vertex -83.677475 63.534050 15.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex -83.306366 63.310757 15.000000
      vertex -72.898163 63.227364 15.000000
      vertex -83.677475 63.534050 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 30.000000 15.000000
      vertex -86.092896 18.637129 15.000000
      vertex -87.067932 23.423172 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 30.000000 15.000000
      vertex -87.067932 23.423172 15.000000
      vertex -87.518509 28.286697 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 30.000000 15.000000
      vertex -87.518509 28.286697 15.000000
      vertex -87.551132 30.000978 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -87.439316 33.170410 15.000000
      vertex -93.972061 30.000000 15.000000
      vertex -87.551132 30.000978 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -82.621429 9.521455 15.000000
      vertex -84.070580 3.715907 15.000000
      vertex -83.677498 3.534048 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -82.621429 9.521455 15.000000
      vertex -87.795883 3.310756 15.000000
      vertex -87.424759 3.534048 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -82.621429 9.521455 15.000000
      vertex -87.424759 3.534048 15.000000
      vertex -87.031685 3.715907 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -86.621246 3.854200 15.000000
      vertex -82.621429 9.521455 15.000000
      vertex -87.031685 3.715907 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -82.621429 9.521455 15.000000
      vertex -86.621246 3.854200 15.000000
      vertex -86.198265 3.947306 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -82.621429 9.521455 15.000000
      vertex -86.198265 3.947306 15.000000
      vertex -85.767685 3.994134 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -85.334579 3.994134 15.000000
      vertex -82.621429 9.521455 15.000000
      vertex -85.767685 3.994134 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -80.165909 5.299218 15.000000
      vertex -82.621429 9.521455 15.000000
      vertex -83.677498 3.534048 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -82.621429 9.521455 15.000000
      vertex -85.334579 3.994134 15.000000
      vertex -84.904007 3.947306 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -82.621429 9.521455 15.000000
      vertex -84.904007 3.947306 15.000000
      vertex -84.481018 3.854200 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -84.070580 3.715907 15.000000
      vertex -82.621429 9.521455 15.000000
      vertex -84.481018 3.854200 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -80.165909 5.299218 15.000000
      vertex -83.677498 3.534048 15.000000
      vertex -83.306389 3.310756 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -80.165909 5.299218 15.000000
      vertex -83.306389 3.310756 15.000000
      vertex -82.961586 3.048648 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -82.647156 2.750798 15.000000
      vertex -80.165909 5.299218 15.000000
      vertex -82.961586 3.048648 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -80.165909 5.299218 15.000000
      vertex -82.647156 2.750798 15.000000
      vertex -82.366760 2.420697 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -80.165909 5.299218 15.000000
      vertex -82.366760 2.420697 15.000000
      vertex -82.123703 2.062216 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -77.267235 1.367985 15.000000
      vertex -80.165909 5.299218 15.000000
      vertex -82.123703 2.062216 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -77.267235 1.367985 15.000000
      vertex -82.123703 2.062216 15.000000
      vertex -81.920830 1.679556 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -81.760521 1.277206 15.000000
      vertex -77.267235 1.367985 15.000000
      vertex -81.920830 1.679556 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -94.147072 -7.809444 15.000000
      vertex -89.551132 -0.000000 15.000000
      vertex -89.527679 0.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -94.147072 -7.809444 15.000000
      vertex -89.527679 0.432476 15.000000
      vertex -89.457619 0.859882 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -94.147072 -7.809444 15.000000
      vertex -89.341743 -1.277206 15.000000
      vertex -89.457619 -0.859882 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -94.147072 -7.809444 15.000000
      vertex -89.457619 -0.859882 15.000000
      vertex -89.527679 -0.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -89.551132 -0.000000 15.000000
      vertex -94.147072 -7.809444 15.000000
      vertex -89.527679 -0.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -77.267235 1.367985 15.000000
      vertex -81.760521 1.277206 15.000000
      vertex -81.644646 0.859882 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -77.267235 1.367985 15.000000
      vertex -81.644646 0.859882 15.000000
      vertex -81.574585 0.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -77.255203 0.221927 15.000000
      vertex -77.267235 1.367985 15.000000
      vertex -81.574585 0.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -77.255203 0.221927 15.000000
      vertex -81.574585 0.432476 15.000000
      vertex -81.551132 -0.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -77.367149 -0.918714 15.000000
      vertex -77.255203 0.221927 15.000000
      vertex -81.551132 -0.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -77.367149 -0.918714 15.000000
      vertex -81.551132 -0.000000 15.000000
      vertex -81.574585 -0.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -77.601768 -2.040565 15.000000
      vertex -77.367149 -0.918714 15.000000
      vertex -81.574585 -0.432476 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -77.601768 -2.040565 15.000000
      vertex -81.574585 -0.432476 15.000000
      vertex -81.644646 -0.859882 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -77.956306 -3.130472 15.000000
      vertex -77.601768 -2.040565 15.000000
      vertex -81.644646 -0.859882 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -94.147072 -7.809444 15.000000
      vertex -89.457619 0.859882 15.000000
      vertex -89.341743 1.277206 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -94.147072 -7.809444 15.000000
      vertex -89.341743 1.277206 15.000000
      vertex -89.181427 1.679556 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -84.604889 13.984954 15.000000
      vertex -94.147072 -7.809444 15.000000
      vertex -89.181427 1.679556 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -84.604889 13.984954 15.000000
      vertex -89.181427 1.679556 15.000000
      vertex -88.978561 2.062216 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -84.604889 13.984954 15.000000
      vertex -88.978561 2.062216 15.000000
      vertex -88.735504 2.420697 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -84.604889 13.984954 15.000000
      vertex -88.735504 2.420697 15.000000
      vertex -88.455109 2.750798 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -82.621429 9.521455 15.000000
      vertex -84.604889 13.984954 15.000000
      vertex -88.455109 2.750798 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -82.621429 9.521455 15.000000
      vertex -88.455109 2.750798 15.000000
      vertex -88.140671 3.048648 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -87.795883 3.310756 15.000000
      vertex -82.621429 9.521455 15.000000
      vertex -88.140671 3.048648 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -77.956306 -3.130472 15.000000
      vertex -81.644646 -0.859882 15.000000
      vertex -81.760521 -1.277206 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -77.956306 -3.130472 15.000000
      vertex -81.760521 -1.277206 15.000000
      vertex -81.920830 -1.679556 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -78.426598 -4.175659 15.000000
      vertex -77.956306 -3.130472 15.000000
      vertex -81.920830 -1.679556 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -78.426598 -4.175659 15.000000
      vertex -81.920830 -1.679556 15.000000
      vertex -82.123703 -2.062216 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -79.007141 -5.163870 15.000000
      vertex -78.426598 -4.175659 15.000000
      vertex -82.123703 -2.062216 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -79.007141 -5.163870 15.000000
      vertex -82.123703 -2.062216 15.000000
      vertex -82.366760 -2.420697 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -79.691124 -6.083521 15.000000
      vertex -79.007141 -5.163870 15.000000
      vertex -82.366760 -2.420697 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -79.691124 -6.083521 15.000000
      vertex -82.366760 -2.420697 15.000000
      vertex -82.647156 -2.750798 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -79.691124 -6.083521 15.000000
      vertex -82.647156 -2.750798 15.000000
      vertex -82.961586 -3.048648 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -80.470543 -6.923829 15.000000
      vertex -79.691124 -6.083521 15.000000
      vertex -82.961586 -3.048648 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -80.470543 -6.923829 15.000000
      vertex -82.961586 -3.048648 15.000000
      vertex -83.306389 -3.310756 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -81.336227 -7.674942 15.000000
      vertex -80.470543 -6.923829 15.000000
      vertex -83.306389 -3.310756 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -81.336227 -7.674942 15.000000
      vertex -83.306389 -3.310756 15.000000
      vertex -83.677498 -3.534048 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -82.278061 -8.328054 15.000000
      vertex -81.336227 -7.674942 15.000000
      vertex -83.677498 -3.534048 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -82.278061 -8.328054 15.000000
      vertex -83.677498 -3.534048 15.000000
      vertex -84.070580 -3.715907 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -83.284981 -8.875509 15.000000
      vertex -82.278061 -8.328054 15.000000
      vertex -84.070580 -3.715907 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -83.284981 -8.875509 15.000000
      vertex -84.070580 -3.715907 15.000000
      vertex -84.481018 -3.854200 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -84.345184 -9.310886 15.000000
      vertex -83.284981 -8.875509 15.000000
      vertex -84.481018 -3.854200 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -84.345184 -9.310886 15.000000
      vertex -84.481018 -3.854200 15.000000
      vertex -84.904007 -3.947306 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -85.446251 -9.629083 15.000000
      vertex -84.345184 -9.310886 15.000000
      vertex -84.904007 -3.947306 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -85.446251 -9.629083 15.000000
      vertex -84.904007 -3.947306 15.000000
      vertex -85.334579 -3.994134 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -86.575264 -9.826368 15.000000
      vertex -85.446251 -9.629083 15.000000
      vertex -85.334579 -3.994134 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -86.575264 -9.826368 15.000000
      vertex -85.334579 -3.994134 15.000000
      vertex -85.767685 -3.994134 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -87.718994 -9.900431 15.000000
      vertex -86.575264 -9.826368 15.000000
      vertex -85.767685 -3.994134 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -87.718994 -9.900431 15.000000
      vertex -85.767685 -3.994134 15.000000
      vertex -86.198265 -3.947306 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -88.864021 -9.850399 15.000000
      vertex -87.718994 -9.900431 15.000000
      vertex -86.198265 -3.947306 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -88.864021 -9.850399 15.000000
      vertex -86.198265 -3.947306 15.000000
      vertex -86.621246 -3.854200 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -89.996925 -9.676861 15.000000
      vertex -88.864021 -9.850399 15.000000
      vertex -86.621246 -3.854200 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -89.996925 -9.676861 15.000000
      vertex -86.621246 -3.854200 15.000000
      vertex -87.031685 -3.715907 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -91.104431 -9.381852 15.000000
      vertex -89.996925 -9.676861 15.000000
      vertex -87.031685 -3.715907 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -91.104431 -9.381852 15.000000
      vertex -87.031685 -3.715907 15.000000
      vertex -87.424759 -3.534048 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -92.173546 -8.968830 15.000000
      vertex -91.104431 -9.381852 15.000000
      vertex -87.424759 -3.534048 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -92.173546 -8.968830 15.000000
      vertex -87.424759 -3.534048 15.000000
      vertex -87.795883 -3.310756 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -93.191734 -8.442637 15.000000
      vertex -92.173546 -8.968830 15.000000
      vertex -87.795883 -3.310756 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.191734 -8.442637 15.000000
      vertex -87.795883 -3.310756 15.000000
      vertex -88.140671 -3.048648 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -94.147072 -7.809444 15.000000
      vertex -93.191734 -8.442637 15.000000
      vertex -88.140671 -3.048648 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -94.147072 -7.809444 15.000000
      vertex -88.140671 -3.048648 15.000000
      vertex -88.455109 -2.750798 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -88.735504 -2.420697 15.000000
      vertex -94.147072 -7.809444 15.000000
      vertex -88.455109 -2.750798 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -94.147072 -7.809444 15.000000
      vertex -88.735504 -2.420697 15.000000
      vertex -88.978561 -2.062216 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -94.147072 -7.809444 15.000000
      vertex -88.978561 -2.062216 15.000000
      vertex -89.181427 -1.679556 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -89.341743 -1.277206 15.000000
      vertex -94.147072 -7.809444 15.000000
      vertex -89.181427 -1.679556 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -94.147072 -7.809444 15.000000
      vertex -84.604889 13.984954 15.000000
      vertex -86.092896 18.637129 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -94.147072 -7.809444 15.000000
      vertex -86.092896 18.637129 15.000000
      vertex -93.972061 30.000000 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -95.028343 -7.076672 15.000000
      vertex -94.147072 -7.809444 15.000000
      vertex -93.972061 30.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -95.028343 -7.076672 15.000000
      vertex -93.972061 30.000000 15.000000
      vertex -95.825218 -6.252914 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -98.392998 -0.000000 15.000000
      vertex -93.972061 30.000000 15.000000
      vertex -98.392998 30.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 30.000000 15.000000
      vertex -98.392998 -0.000000 15.000000
      vertex -98.257126 -1.138039 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 30.000000 15.000000
      vertex -98.257126 -1.138039 15.000000
      vertex -97.999008 -2.254716 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -97.621666 -3.336940 15.000000
      vertex -93.972061 30.000000 15.000000
      vertex -97.999008 -2.254716 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 30.000000 15.000000
      vertex -97.621666 -3.336940 15.000000
      vertex -97.129532 -4.372022 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 30.000000 15.000000
      vertex -97.129532 -4.372022 15.000000
      vertex -96.528366 -5.347826 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -95.825218 -6.252914 15.000000
      vertex -93.972061 30.000000 15.000000
      vertex -96.528366 -5.347826 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -98.392998 61.323826 15.000000
      vertex -98.392998 30.000000 15.000000
      vertex -93.972061 30.000000 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -98.392998 61.323826 15.000000
      vertex -93.972061 30.000000 15.000000
      vertex -93.972061 72.000000 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex -98.267982 63.648006 15.000000
      vertex -98.392998 61.323826 15.000000
      vertex -93.972061 72.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -92.544991 76.129631 15.000000
      vertex -94.041954 74.347336 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -94.041954 74.347336 15.000000
      vertex -95.339081 72.414757 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -96.421417 70.354179 15.000000
      vertex -93.972061 72.000000 15.000000
      vertex -95.339081 72.414757 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -96.421417 70.354179 15.000000
      vertex -97.276474 68.189384 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -93.972061 72.000000 15.000000
      vertex -97.276474 68.189384 15.000000
      vertex -97.894371 65.945366 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -98.267982 63.648006 15.000000
      vertex -93.972061 72.000000 15.000000
      vertex -97.894371 65.945366 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 54.539230 81.974129 15.000000
      vertex 54.188740 81.561508 15.000000
      vertex 61.308319 79.666428 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 54.539230 81.974129 15.000000
      vertex 61.308319 79.666428 15.000000
      vertex 54.843048 82.422234 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 50.288071 80.007332 15.000000
      vertex 46.875835 65.689217 15.000000
      vertex 50.829460 80.007332 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 65.689217 15.000000
      vertex 52.409454 80.355118 15.000000
      vertex 51.896404 80.182243 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 65.689217 15.000000
      vertex 51.896404 80.182243 15.000000
      vertex 51.367676 80.065872 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 50.829460 80.007332 15.000000
      vertex 46.875835 65.689217 15.000000
      vertex 51.367676 80.065872 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.308319 79.666428 15.000000
      vertex 54.188740 81.561508 15.000000
      vertex 53.795696 81.189194 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.308319 79.666428 15.000000
      vertex 53.795696 81.189194 15.000000
      vertex 53.364697 80.861557 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 65.689217 15.000000
      vertex 61.308319 79.666428 15.000000
      vertex 53.364697 80.861557 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 65.689217 15.000000
      vertex 53.364697 80.861557 15.000000
      vertex 52.900806 80.582443 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 52.409454 80.355118 15.000000
      vertex 46.875835 65.689217 15.000000
      vertex 52.900806 80.582443 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 65.689217 15.000000
      vertex 50.288071 80.007332 15.000000
      vertex 49.749855 80.065872 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 65.689217 15.000000
      vertex 49.749855 80.065872 15.000000
      vertex 49.221119 80.182243 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 48.708073 80.355118 15.000000
      vertex 46.875835 65.689217 15.000000
      vertex 49.221119 80.182243 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.578300 81.974129 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 46.928787 81.561508 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 46.578300 81.974129 15.000000
      vertex 46.274479 82.422234 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 46.274479 82.422234 15.000000
      vertex 46.020889 82.900551 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 45.820496 83.403488 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 46.020889 82.900551 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 65.689217 15.000000
      vertex 48.708073 80.355118 15.000000
      vertex 48.216724 80.582443 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.875835 65.689217 15.000000
      vertex 48.216724 80.582443 15.000000
      vertex 47.752827 80.861557 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 46.875835 65.689217 15.000000
      vertex 47.752827 80.861557 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 47.752827 80.861557 15.000000
      vertex 47.321835 81.189194 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.928787 81.561508 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 47.321835 81.189194 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 94.112053 15.000000
      vertex 45.588074 85.540596 15.000000
      vertex 45.675663 86.074852 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 94.112053 15.000000
      vertex 45.675663 86.074852 15.000000
      vertex 45.820496 86.596512 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.020889 87.099449 15.000000
      vertex 25.003807 94.112053 15.000000
      vertex 45.820496 86.596512 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 94.112053 15.000000
      vertex 46.020889 87.099449 15.000000
      vertex 46.274479 87.577766 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 94.112053 15.000000
      vertex 46.274479 87.577766 15.000000
      vertex 46.578300 88.025871 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 46.928787 88.438499 15.000000
      vertex 25.003807 94.112053 15.000000
      vertex 46.578300 88.025871 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 49.221119 89.817749 15.000000
      vertex 49.600864 96.961708 15.000000
      vertex 48.708073 89.644890 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 45.820496 83.403488 15.000000
      vertex 45.675663 83.925148 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 72.000000 15.000000
      vertex 45.675663 83.925148 15.000000
      vertex 45.588074 84.459404 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 94.112053 15.000000
      vertex 25.003807 72.000000 15.000000
      vertex 45.588074 84.459404 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 94.112053 15.000000
      vertex 45.588074 84.459404 15.000000
      vertex 45.558765 85.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 45.588074 85.540596 15.000000
      vertex 25.003807 94.112053 15.000000
      vertex 45.558765 85.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 94.112053 15.000000
      vertex 46.928787 88.438499 15.000000
      vertex 47.321835 88.810806 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 25.003807 94.112053 15.000000
      vertex 47.321835 88.810806 15.000000
      vertex 47.752827 89.138451 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 49.600864 96.961708 15.000000
      vertex 25.003807 94.112053 15.000000
      vertex 47.752827 89.138451 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 49.600864 96.961708 15.000000
      vertex 47.752827 89.138451 15.000000
      vertex 48.216724 89.417564 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 48.708073 89.644890 15.000000
      vertex 49.600864 96.961708 15.000000
      vertex 48.216724 89.417564 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 49.600864 96.961708 15.000000
      vertex 49.221119 89.817749 15.000000
      vertex 49.749855 89.934135 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 49.600864 96.961708 15.000000
      vertex 49.749855 89.934135 15.000000
      vertex 50.288071 89.992668 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 50.907948 96.929337 15.000000
      vertex 49.600864 96.961708 15.000000
      vertex 50.288071 89.992668 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 50.907948 96.929337 15.000000
      vertex 50.288071 89.992668 15.000000
      vertex 50.829460 89.992668 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 52.204327 96.759293 15.000000
      vertex 50.907948 96.929337 15.000000
      vertex 50.829460 89.992668 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 52.204327 96.759293 15.000000
      vertex 50.829460 89.992668 15.000000
      vertex 51.367676 89.934135 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 53.475536 96.453468 15.000000
      vertex 52.204327 96.759293 15.000000
      vertex 51.367676 89.934135 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 53.475536 96.453468 15.000000
      vertex 51.367676 89.934135 15.000000
      vertex 51.896404 89.817749 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 54.707409 96.015282 15.000000
      vertex 53.475536 96.453468 15.000000
      vertex 51.896404 89.817749 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 54.707409 96.015282 15.000000
      vertex 51.896404 89.817749 15.000000
      vertex 52.409454 89.644890 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 55.886192 95.449615 15.000000
      vertex 54.707409 96.015282 15.000000
      vertex 52.409454 89.644890 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 55.886192 95.449615 15.000000
      vertex 52.409454 89.644890 15.000000
      vertex 52.900806 89.417564 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 56.998745 94.762787 15.000000
      vertex 55.886192 95.449615 15.000000
      vertex 52.900806 89.417564 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 56.998745 94.762787 15.000000
      vertex 52.900806 89.417564 15.000000
      vertex 53.364697 89.138451 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 58.032654 93.962448 15.000000
      vertex 56.998745 94.762787 15.000000
      vertex 53.364697 89.138451 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 58.032654 93.962448 15.000000
      vertex 53.364697 89.138451 15.000000
      vertex 53.795696 88.810806 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 58.976387 93.057526 15.000000
      vertex 58.032654 93.962448 15.000000
      vertex 53.795696 88.810806 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 58.976387 93.057526 15.000000
      vertex 53.795696 88.810806 15.000000
      vertex 54.188740 88.438499 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 59.819420 92.058121 15.000000
      vertex 58.976387 93.057526 15.000000
      vertex 54.188740 88.438499 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 59.819420 92.058121 15.000000
      vertex 54.188740 88.438499 15.000000
      vertex 54.539230 88.025871 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 60.552345 90.975380 15.000000
      vertex 59.819420 92.058121 15.000000
      vertex 54.539230 88.025871 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 60.552345 90.975380 15.000000
      vertex 54.539230 88.025871 15.000000
      vertex 54.843048 87.577766 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.166992 89.821373 15.000000
      vertex 60.552345 90.975380 15.000000
      vertex 54.843048 87.577766 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.166992 89.821373 15.000000
      vertex 54.843048 87.577766 15.000000
      vertex 55.096642 87.099449 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.656498 88.608986 15.000000
      vertex 61.166992 89.821373 15.000000
      vertex 55.096642 87.099449 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.656498 88.608986 15.000000
      vertex 55.096642 87.099449 15.000000
      vertex 55.297028 86.596512 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 62.015408 87.351730 15.000000
      vertex 61.656498 88.608986 15.000000
      vertex 55.297028 86.596512 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 62.015408 87.351730 15.000000
      vertex 55.297028 86.596512 15.000000
      vertex 55.441868 86.074852 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 62.239719 86.063637 15.000000
      vertex 62.015408 87.351730 15.000000
      vertex 55.441868 86.074852 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 62.239719 86.063637 15.000000
      vertex 55.441868 86.074852 15.000000
      vertex 55.529453 85.540596 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 62.326927 84.759064 15.000000
      vertex 62.239719 86.063637 15.000000
      vertex 55.529453 85.540596 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 62.326927 84.759064 15.000000
      vertex 55.529453 85.540596 15.000000
      vertex 55.558762 85.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 62.276058 83.452576 15.000000
      vertex 62.326927 84.759064 15.000000
      vertex 55.558762 85.000000 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 62.276058 83.452576 15.000000
      vertex 55.558762 85.000000 15.000000
      vertex 55.529453 84.459404 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 62.087681 82.158730 15.000000
      vertex 62.276058 83.452576 15.000000
      vertex 55.529453 84.459404 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 62.087681 82.158730 15.000000
      vertex 55.529453 84.459404 15.000000
      vertex 55.441868 83.925148 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 61.763901 80.891975 15.000000
      vertex 62.087681 82.158730 15.000000
      vertex 55.441868 83.925148 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.763901 80.891975 15.000000
      vertex 55.441868 83.925148 15.000000
      vertex 55.297028 83.403488 15.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 61.308319 79.666428 15.000000
      vertex 61.763901 80.891975 15.000000
      vertex 55.297028 83.403488 15.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 61.308319 79.666428 15.000000
      vertex 55.297028 83.403488 15.000000
      vertex 55.096642 82.900551 15.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 54.843048 82.422234 15.000000
      vertex 61.308319 79.666428 15.000000
      vertex 55.096642 82.900551 15.000000
    endloop
  endfacet
  facet normal 0.998533 -0.054142 0.000000
    outer loop
      vertex 45.588058 -24.459404 15.000000
      vertex 45.558746 -25.000000 15.000000
      vertex 45.558746 -25.000000 0.000000
    endloop
  endfacet
  facet normal 0.998533 -0.054142 0.000000
    outer loop
      vertex 45.588058 -24.459404 15.000000
      vertex 45.558746 -25.000000 0.000000
      vertex 45.588058 -24.459404 0.000000
    endloop
  endfacet
  facet normal 0.986827 -0.161780 0.000000
    outer loop
      vertex 45.675644 -23.925148 15.000000
      vertex 45.588058 -24.459404 15.000000
      vertex 45.588058 -24.459404 0.000000
    endloop
  endfacet
  facet normal 0.986827 -0.161780 0.000000
    outer loop
      vertex 45.675644 -23.925148 15.000000
      vertex 45.588058 -24.459404 0.000000
      vertex 45.675644 -23.925148 0.000000
    endloop
  endfacet
  facet normal 0.963550 -0.267527 0.000000
    outer loop
      vertex 45.820480 -23.403492 15.000000
      vertex 45.675644 -23.925148 15.000000
      vertex 45.675644 -23.925148 0.000000
    endloop
  endfacet
  facet normal 0.963550 -0.267527 0.000000
    outer loop
      vertex 45.820480 -23.403492 15.000000
      vertex 45.675644 -23.925148 0.000000
      vertex 45.820480 -23.403492 0.000000
    endloop
  endfacet
  facet normal 0.928976 -0.370140 0.000000
    outer loop
      vertex 46.020870 -22.900555 15.000000
      vertex 45.820480 -23.403492 15.000000
      vertex 45.820480 -23.403492 0.000000
    endloop
  endfacet
  facet normal 0.928976 -0.370140 0.000000
    outer loop
      vertex 46.020870 -22.900555 15.000000
      vertex 45.820480 -23.403492 0.000000
      vertex 46.020870 -22.900555 0.000000
    endloop
  endfacet
  facet normal 0.883514 -0.468405 0.000000
    outer loop
      vertex 46.274460 -22.422230 15.000000
      vertex 46.020870 -22.900555 15.000000
      vertex 46.020870 -22.900555 0.000000
    endloop
  endfacet
  facet normal 0.883514 -0.468405 0.000000
    outer loop
      vertex 46.274460 -22.422230 15.000000
      vertex 46.020870 -22.900555 0.000000
      vertex 46.274460 -22.422230 0.000000
    endloop
  endfacet
  facet normal 0.827688 -0.561189 0.000000
    outer loop
      vertex 46.578281 -21.974129 15.000000
      vertex 46.274460 -22.422230 15.000000
      vertex 46.274460 -22.422230 0.000000
    endloop
  endfacet
  facet normal 0.827688 -0.561189 0.000000
    outer loop
      vertex 46.578281 -21.974129 15.000000
      vertex 46.274460 -22.422230 0.000000
      vertex 46.578281 -21.974129 0.000000
    endloop
  endfacet
  facet normal 0.762158 -0.647391 0.000000
    outer loop
      vertex 46.928772 -21.561504 15.000000
      vertex 46.578281 -21.974129 15.000000
      vertex 46.578281 -21.974129 0.000000
    endloop
  endfacet
  facet normal 0.762158 -0.647391 0.000000
    outer loop
      vertex 46.928772 -21.561504 15.000000
      vertex 46.578281 -21.974129 0.000000
      vertex 46.928772 -21.561504 0.000000
    endloop
  endfacet
  facet normal 0.687703 -0.725992 0.000000
    outer loop
      vertex 47.321815 -21.189190 15.000000
      vertex 46.928772 -21.561504 15.000000
      vertex 46.928772 -21.561504 0.000000
    endloop
  endfacet
  facet normal 0.687703 -0.725992 0.000000
    outer loop
      vertex 47.321815 -21.189190 15.000000
      vertex 46.928772 -21.561504 0.000000
      vertex 47.321815 -21.189190 0.000000
    endloop
  endfacet
  facet normal 0.605174 -0.796093 0.000000
    outer loop
      vertex 47.752811 -20.861555 15.000000
      vertex 47.321815 -21.189190 15.000000
      vertex 47.321815 -21.189190 0.000000
    endloop
  endfacet
  facet normal 0.605174 -0.796093 0.000000
    outer loop
      vertex 47.752811 -20.861555 15.000000
      vertex 47.321815 -21.189190 0.000000
      vertex 47.752811 -20.861555 0.000000
    endloop
  endfacet
  facet normal 0.515554 -0.856857 0.000000
    outer loop
      vertex 48.216705 -20.582439 15.000000
      vertex 47.752811 -20.861555 15.000000
      vertex 47.752811 -20.861555 0.000000
    endloop
  endfacet
  facet normal 0.515554 -0.856857 0.000000
    outer loop
      vertex 48.216705 -20.582439 15.000000
      vertex 47.752811 -20.861555 0.000000
      vertex 48.216705 -20.582439 0.000000
    endloop
  endfacet
  facet normal 0.419892 -0.907574 0.000000
    outer loop
      vertex 48.708054 -20.355116 15.000000
      vertex 48.216705 -20.582439 15.000000
      vertex 48.216705 -20.582439 0.000000
    endloop
  endfacet
  facet normal 0.419892 -0.907574 0.000000
    outer loop
      vertex 48.708054 -20.355116 15.000000
      vertex 48.216705 -20.582439 0.000000
      vertex 48.708054 -20.355116 0.000000
    endloop
  endfacet
  facet normal 0.319296 -0.947655 0.000000
    outer loop
      vertex 49.221107 -20.182251 15.000000
      vertex 48.708054 -20.355116 15.000000
      vertex 48.708054 -20.355116 0.000000
    endloop
  endfacet
  facet normal 0.319296 -0.947655 0.000000
    outer loop
      vertex 49.221107 -20.182251 15.000000
      vertex 48.708054 -20.355116 0.000000
      vertex 49.221107 -20.182251 0.000000
    endloop
  endfacet
  facet normal 0.214972 -0.976620 0.000000
    outer loop
      vertex 49.749836 -20.065868 15.000000
      vertex 49.221107 -20.182251 15.000000
      vertex 49.221107 -20.182251 0.000000
    endloop
  endfacet
  facet normal 0.214972 -0.976620 0.000000
    outer loop
      vertex 49.749836 -20.065868 15.000000
      vertex 49.221107 -20.182251 0.000000
      vertex 49.749836 -20.065868 0.000000
    endloop
  endfacet
  facet normal 0.108123 -0.994138 0.000000
    outer loop
      vertex 50.288052 -20.007332 15.000000
      vertex 49.749836 -20.065868 15.000000
      vertex 49.749836 -20.065868 0.000000
    endloop
  endfacet
  facet normal 0.108123 -0.994138 0.000000
    outer loop
      vertex 50.288052 -20.007332 15.000000
      vertex 49.749836 -20.065868 0.000000
      vertex 50.288052 -20.007332 0.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex 50.829441 -20.007332 15.000000
      vertex 50.288052 -20.007332 15.000000
      vertex 50.288052 -20.007332 0.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex 50.829441 -20.007332 15.000000
      vertex 50.288052 -20.007332 0.000000
      vertex 50.829441 -20.007332 0.000000
    endloop
  endfacet
  facet normal -0.108123 -0.994138 0.000000
    outer loop
      vertex 51.367657 -20.065868 15.000000
      vertex 50.829441 -20.007332 15.000000
      vertex 50.829441 -20.007332 0.000000
    endloop
  endfacet
  facet normal -0.108123 -0.994138 -0.000000
    outer loop
      vertex 51.367657 -20.065868 15.000000
      vertex 50.829441 -20.007332 0.000000
      vertex 51.367657 -20.065868 0.000000
    endloop
  endfacet
  facet normal -0.214970 -0.976621 0.000000
    outer loop
      vertex 51.896389 -20.182251 15.000000
      vertex 51.367657 -20.065868 15.000000
      vertex 51.367657 -20.065868 0.000000
    endloop
  endfacet
  facet normal -0.214970 -0.976621 -0.000000
    outer loop
      vertex 51.896389 -20.182251 15.000000
      vertex 51.367657 -20.065868 0.000000
      vertex 51.896389 -20.182251 0.000000
    endloop
  endfacet
  facet normal -0.319301 -0.947653 0.000000
    outer loop
      vertex 52.409435 -20.355116 15.000000
      vertex 51.896389 -20.182251 15.000000
      vertex 51.896389 -20.182251 0.000000
    endloop
  endfacet
  facet normal -0.319301 -0.947653 -0.000000
    outer loop
      vertex 52.409435 -20.355116 15.000000
      vertex 51.896389 -20.182251 0.000000
      vertex 52.409435 -20.355116 0.000000
    endloop
  endfacet
  facet normal -0.419889 -0.907576 0.000000
    outer loop
      vertex 52.900787 -20.582439 15.000000
      vertex 52.409435 -20.355116 15.000000
      vertex 52.409435 -20.355116 0.000000
    endloop
  endfacet
  facet normal -0.419889 -0.907576 -0.000000
    outer loop
      vertex 52.900787 -20.582439 15.000000
      vertex 52.409435 -20.355116 0.000000
      vertex 52.900787 -20.582439 0.000000
    endloop
  endfacet
  facet normal -0.515554 -0.856857 0.000000
    outer loop
      vertex 53.364681 -20.861555 15.000000
      vertex 52.900787 -20.582439 15.000000
      vertex 52.900787 -20.582439 0.000000
    endloop
  endfacet
  facet normal -0.515554 -0.856857 -0.000000
    outer loop
      vertex 53.364681 -20.861555 15.000000
      vertex 52.900787 -20.582439 0.000000
      vertex 53.364681 -20.861555 0.000000
    endloop
  endfacet
  facet normal -0.605174 -0.796093 0.000000
    outer loop
      vertex 53.795677 -21.189190 15.000000
      vertex 53.364681 -20.861555 15.000000
      vertex 53.364681 -20.861555 0.000000
    endloop
  endfacet
  facet normal -0.605174 -0.796093 -0.000000
    outer loop
      vertex 53.795677 -21.189190 15.000000
      vertex 53.364681 -20.861555 0.000000
      vertex 53.795677 -21.189190 0.000000
    endloop
  endfacet
  facet normal -0.687700 -0.725995 0.000000
    outer loop
      vertex 54.188725 -21.561504 15.000000
      vertex 53.795677 -21.189190 15.000000
      vertex 53.795677 -21.189190 0.000000
    endloop
  endfacet
  facet normal -0.687700 -0.725995 -0.000000
    outer loop
      vertex 54.188725 -21.561504 15.000000
      vertex 53.795677 -21.189190 0.000000
      vertex 54.188725 -21.561504 0.000000
    endloop
  endfacet
  facet normal -0.762162 -0.647387 0.000000
    outer loop
      vertex 54.539211 -21.974129 15.000000
      vertex 54.188725 -21.561504 15.000000
      vertex 54.188725 -21.561504 0.000000
    endloop
  endfacet
  facet normal -0.762162 -0.647387 -0.000000
    outer loop
      vertex 54.539211 -21.974129 15.000000
      vertex 54.188725 -21.561504 0.000000
      vertex 54.539211 -21.974129 0.000000
    endloop
  endfacet
  facet normal -0.827691 -0.561184 0.000000
    outer loop
      vertex 54.843029 -22.422230 15.000000
      vertex 54.539211 -21.974129 15.000000
      vertex 54.539211 -21.974129 0.000000
    endloop
  endfacet
  facet normal -0.827691 -0.561184 -0.000000
    outer loop
      vertex 54.843029 -22.422230 15.000000
      vertex 54.539211 -21.974129 0.000000
      vertex 54.843029 -22.422230 0.000000
    endloop
  endfacet
  facet normal -0.883511 -0.468411 0.000000
    outer loop
      vertex 55.096622 -22.900555 15.000000
      vertex 54.843029 -22.422230 15.000000
      vertex 54.843029 -22.422230 0.000000
    endloop
  endfacet
  facet normal -0.883511 -0.468411 -0.000000
    outer loop
      vertex 55.096622 -22.900555 15.000000
      vertex 54.843029 -22.422230 0.000000
      vertex 55.096622 -22.900555 0.000000
    endloop
  endfacet
  facet normal -0.928976 -0.370140 0.000000
    outer loop
      vertex 55.297012 -23.403492 15.000000
      vertex 55.096622 -22.900555 15.000000
      vertex 55.096622 -22.900555 0.000000
    endloop
  endfacet
  facet normal -0.928976 -0.370140 -0.000000
    outer loop
      vertex 55.297012 -23.403492 15.000000
      vertex 55.096622 -22.900555 0.000000
      vertex 55.297012 -23.403492 0.000000
    endloop
  endfacet
  facet normal -0.963550 -0.267527 0.000000
    outer loop
      vertex 55.441849 -23.925148 15.000000
      vertex 55.297012 -23.403492 15.000000
      vertex 55.297012 -23.403492 0.000000
    endloop
  endfacet
  facet normal -0.963550 -0.267527 -0.000000
    outer loop
      vertex 55.441849 -23.925148 15.000000
      vertex 55.297012 -23.403492 0.000000
      vertex 55.441849 -23.925148 0.000000
    endloop
  endfacet
  facet normal -0.986826 -0.161786 0.000000
    outer loop
      vertex 55.529438 -24.459404 15.000000
      vertex 55.441849 -23.925148 15.000000
      vertex 55.441849 -23.925148 0.000000
    endloop
  endfacet
  facet normal -0.986826 -0.161786 -0.000000
    outer loop
      vertex 55.529438 -24.459404 15.000000
      vertex 55.441849 -23.925148 0.000000
      vertex 55.529438 -24.459404 0.000000
    endloop
  endfacet
  facet normal -0.998533 -0.054142 0.000000
    outer loop
      vertex 55.558750 -25.000000 15.000000
      vertex 55.529438 -24.459404 15.000000
      vertex 55.529438 -24.459404 0.000000
    endloop
  endfacet
  facet normal -0.998533 -0.054142 -0.000000
    outer loop
      vertex 55.558750 -25.000000 15.000000
      vertex 55.529438 -24.459404 0.000000
      vertex 55.558750 -25.000000 0.000000
    endloop
  endfacet
  facet normal -0.998533 0.054142 0.000000
    outer loop
      vertex 55.529438 -25.540596 15.000000
      vertex 55.558750 -25.000000 15.000000
      vertex 55.558750 -25.000000 0.000000
    endloop
  endfacet
  facet normal -0.998533 0.054142 0.000000
    outer loop
      vertex 55.529438 -25.540596 15.000000
      vertex 55.558750 -25.000000 0.000000
      vertex 55.529438 -25.540596 0.000000
    endloop
  endfacet
  facet normal -0.986826 0.161786 0.000000
    outer loop
      vertex 55.441849 -26.074852 15.000000
      vertex 55.529438 -25.540596 15.000000
      vertex 55.529438 -25.540596 0.000000
    endloop
  endfacet
  facet normal -0.986826 0.161786 0.000000
    outer loop
      vertex 55.441849 -26.074852 15.000000
      vertex 55.529438 -25.540596 0.000000
      vertex 55.441849 -26.074852 0.000000
    endloop
  endfacet
  facet normal -0.963550 0.267528 0.000000
    outer loop
      vertex 55.297012 -26.596506 15.000000
      vertex 55.441849 -26.074852 15.000000
      vertex 55.441849 -26.074852 0.000000
    endloop
  endfacet
  facet normal -0.963550 0.267528 0.000000
    outer loop
      vertex 55.297012 -26.596506 15.000000
      vertex 55.441849 -26.074852 0.000000
      vertex 55.297012 -26.596506 0.000000
    endloop
  endfacet
  facet normal -0.928976 0.370139 0.000000
    outer loop
      vertex 55.096622 -27.099445 15.000000
      vertex 55.297012 -26.596506 15.000000
      vertex 55.297012 -26.596506 0.000000
    endloop
  endfacet
  facet normal -0.928976 0.370139 0.000000
    outer loop
      vertex 55.096622 -27.099445 15.000000
      vertex 55.297012 -26.596506 0.000000
      vertex 55.096622 -27.099445 0.000000
    endloop
  endfacet
  facet normal -0.883510 0.468412 0.000000
    outer loop
      vertex 54.843029 -27.577768 15.000000
      vertex 55.096622 -27.099445 15.000000
      vertex 55.096622 -27.099445 0.000000
    endloop
  endfacet
  facet normal -0.883510 0.468412 0.000000
    outer loop
      vertex 54.843029 -27.577768 15.000000
      vertex 55.096622 -27.099445 0.000000
      vertex 54.843029 -27.577768 0.000000
    endloop
  endfacet
  facet normal -0.827692 0.561183 0.000000
    outer loop
      vertex 54.539211 -28.025871 15.000000
      vertex 54.843029 -27.577768 15.000000
      vertex 54.843029 -27.577768 0.000000
    endloop
  endfacet
  facet normal -0.827692 0.561183 0.000000
    outer loop
      vertex 54.539211 -28.025871 15.000000
      vertex 54.843029 -27.577768 0.000000
      vertex 54.539211 -28.025871 0.000000
    endloop
  endfacet
  facet normal -0.762163 0.647385 0.000000
    outer loop
      vertex 54.188725 -28.438498 15.000000
      vertex 54.539211 -28.025871 15.000000
      vertex 54.539211 -28.025871 0.000000
    endloop
  endfacet
  facet normal -0.762163 0.647385 0.000000
    outer loop
      vertex 54.188725 -28.438498 15.000000
      vertex 54.539211 -28.025871 0.000000
      vertex 54.188725 -28.438498 0.000000
    endloop
  endfacet
  facet normal -0.687698 0.725997 0.000000
    outer loop
      vertex 53.795677 -28.810810 15.000000
      vertex 54.188725 -28.438498 15.000000
      vertex 54.188725 -28.438498 0.000000
    endloop
  endfacet
  facet normal -0.687698 0.725997 0.000000
    outer loop
      vertex 53.795677 -28.810810 15.000000
      vertex 54.188725 -28.438498 0.000000
      vertex 53.795677 -28.810810 0.000000
    endloop
  endfacet
  facet normal -0.605177 0.796091 0.000000
    outer loop
      vertex 53.364681 -29.138447 15.000000
      vertex 53.795677 -28.810810 15.000000
      vertex 53.795677 -28.810810 0.000000
    endloop
  endfacet
  facet normal -0.605177 0.796091 0.000000
    outer loop
      vertex 53.364681 -29.138447 15.000000
      vertex 53.795677 -28.810810 0.000000
      vertex 53.364681 -29.138447 0.000000
    endloop
  endfacet
  facet normal -0.515549 0.856860 0.000000
    outer loop
      vertex 52.900787 -29.417559 15.000000
      vertex 53.364681 -29.138447 15.000000
      vertex 53.364681 -29.138447 0.000000
    endloop
  endfacet
  facet normal -0.515549 0.856860 0.000000
    outer loop
      vertex 52.900787 -29.417559 15.000000
      vertex 53.364681 -29.138447 0.000000
      vertex 52.900787 -29.417559 0.000000
    endloop
  endfacet
  facet normal -0.419892 0.907574 0.000000
    outer loop
      vertex 52.409435 -29.644884 15.000000
      vertex 52.900787 -29.417559 15.000000
      vertex 52.900787 -29.417559 0.000000
    endloop
  endfacet
  facet normal -0.419892 0.907574 0.000000
    outer loop
      vertex 52.409435 -29.644884 15.000000
      vertex 52.900787 -29.417559 0.000000
      vertex 52.409435 -29.644884 0.000000
    endloop
  endfacet
  facet normal -0.319304 0.947652 0.000000
    outer loop
      vertex 51.896389 -29.817751 15.000000
      vertex 52.409435 -29.644884 15.000000
      vertex 52.409435 -29.644884 0.000000
    endloop
  endfacet
  facet normal -0.319304 0.947652 0.000000
    outer loop
      vertex 51.896389 -29.817751 15.000000
      vertex 52.409435 -29.644884 0.000000
      vertex 51.896389 -29.817751 0.000000
    endloop
  endfacet
  facet normal -0.214967 0.976621 0.000000
    outer loop
      vertex 51.367657 -29.934132 15.000000
      vertex 51.896389 -29.817751 15.000000
      vertex 51.896389 -29.817751 0.000000
    endloop
  endfacet
  facet normal -0.214967 0.976621 0.000000
    outer loop
      vertex 51.367657 -29.934132 15.000000
      vertex 51.896389 -29.817751 0.000000
      vertex 51.367657 -29.934132 0.000000
    endloop
  endfacet
  facet normal -0.108123 0.994138 0.000000
    outer loop
      vertex 50.829441 -29.992668 15.000000
      vertex 51.367657 -29.934132 15.000000
      vertex 51.367657 -29.934132 0.000000
    endloop
  endfacet
  facet normal -0.108123 0.994138 0.000000
    outer loop
      vertex 50.829441 -29.992668 15.000000
      vertex 51.367657 -29.934132 0.000000
      vertex 50.829441 -29.992668 0.000000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 50.288052 -29.992668 15.000000
      vertex 50.829441 -29.992668 15.000000
      vertex 50.829441 -29.992668 0.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 50.288052 -29.992668 15.000000
      vertex 50.829441 -29.992668 0.000000
      vertex 50.288052 -29.992668 0.000000
    endloop
  endfacet
  facet normal 0.108123 0.994138 0.000000
    outer loop
      vertex 49.749836 -29.934132 15.000000
      vertex 50.288052 -29.992668 15.000000
      vertex 50.288052 -29.992668 0.000000
    endloop
  endfacet
  facet normal 0.108123 0.994138 0.000000
    outer loop
      vertex 49.749836 -29.934132 15.000000
      vertex 50.288052 -29.992668 0.000000
      vertex 49.749836 -29.934132 0.000000
    endloop
  endfacet
  facet normal 0.214968 0.976621 0.000000
    outer loop
      vertex 49.221107 -29.817751 15.000000
      vertex 49.749836 -29.934132 15.000000
      vertex 49.749836 -29.934132 0.000000
    endloop
  endfacet
  facet normal 0.214968 0.976621 0.000000
    outer loop
      vertex 49.221107 -29.817751 15.000000
      vertex 49.749836 -29.934132 0.000000
      vertex 49.221107 -29.817751 0.000000
    endloop
  endfacet
  facet normal 0.319300 0.947654 0.000000
    outer loop
      vertex 48.708054 -29.644884 15.000000
      vertex 49.221107 -29.817751 15.000000
      vertex 49.221107 -29.817751 0.000000
    endloop
  endfacet
  facet normal 0.319300 0.947654 0.000000
    outer loop
      vertex 48.708054 -29.644884 15.000000
      vertex 49.221107 -29.817751 0.000000
      vertex 48.708054 -29.644884 0.000000
    endloop
  endfacet
  facet normal 0.419894 0.907573 0.000000
    outer loop
      vertex 48.216705 -29.417559 15.000000
      vertex 48.708054 -29.644884 15.000000
      vertex 48.708054 -29.644884 0.000000
    endloop
  endfacet
  facet normal 0.419894 0.907573 0.000000
    outer loop
      vertex 48.216705 -29.417559 15.000000
      vertex 48.708054 -29.644884 0.000000
      vertex 48.216705 -29.417559 0.000000
    endloop
  endfacet
  facet normal 0.515549 0.856860 0.000000
    outer loop
      vertex 47.752811 -29.138447 15.000000
      vertex 48.216705 -29.417559 15.000000
      vertex 48.216705 -29.417559 0.000000
    endloop
  endfacet
  facet normal 0.515549 0.856860 0.000000
    outer loop
      vertex 47.752811 -29.138447 15.000000
      vertex 48.216705 -29.417559 0.000000
      vertex 47.752811 -29.138447 0.000000
    endloop
  endfacet
  facet normal 0.605177 0.796091 0.000000
    outer loop
      vertex 47.321815 -28.810810 15.000000
      vertex 47.752811 -29.138447 15.000000
      vertex 47.752811 -29.138447 0.000000
    endloop
  endfacet
  facet normal 0.605177 0.796091 0.000000
    outer loop
      vertex 47.321815 -28.810810 15.000000
      vertex 47.752811 -29.138447 0.000000
      vertex 47.321815 -28.810810 0.000000
    endloop
  endfacet
  facet normal 0.687701 0.725994 0.000000
    outer loop
      vertex 46.928772 -28.438498 15.000000
      vertex 47.321815 -28.810810 15.000000
      vertex 47.321815 -28.810810 0.000000
    endloop
  endfacet
  facet normal 0.687701 0.725994 0.000000
    outer loop
      vertex 46.928772 -28.438498 15.000000
      vertex 47.321815 -28.810810 0.000000
      vertex 46.928772 -28.438498 0.000000
    endloop
  endfacet
  facet normal 0.762160 0.647389 0.000000
    outer loop
      vertex 46.578281 -28.025871 15.000000
      vertex 46.928772 -28.438498 15.000000
      vertex 46.928772 -28.438498 0.000000
    endloop
  endfacet
  facet normal 0.762160 0.647389 0.000000
    outer loop
      vertex 46.578281 -28.025871 15.000000
      vertex 46.928772 -28.438498 0.000000
      vertex 46.578281 -28.025871 0.000000
    endloop
  endfacet
  facet normal 0.827689 0.561187 0.000000
    outer loop
      vertex 46.274460 -27.577768 15.000000
      vertex 46.578281 -28.025871 15.000000
      vertex 46.578281 -28.025871 0.000000
    endloop
  endfacet
  facet normal 0.827689 0.561187 0.000000
    outer loop
      vertex 46.274460 -27.577768 15.000000
      vertex 46.578281 -28.025871 0.000000
      vertex 46.274460 -27.577768 0.000000
    endloop
  endfacet
  facet normal 0.883513 0.468407 0.000000
    outer loop
      vertex 46.020870 -27.099445 15.000000
      vertex 46.274460 -27.577768 15.000000
      vertex 46.274460 -27.577768 0.000000
    endloop
  endfacet
  facet normal 0.883513 0.468407 0.000000
    outer loop
      vertex 46.020870 -27.099445 15.000000
      vertex 46.274460 -27.577768 0.000000
      vertex 46.020870 -27.099445 0.000000
    endloop
  endfacet
  facet normal 0.928976 0.370139 0.000000
    outer loop
      vertex 45.820480 -26.596506 15.000000
      vertex 46.020870 -27.099445 15.000000
      vertex 46.020870 -27.099445 0.000000
    endloop
  endfacet
  facet normal 0.928976 0.370139 0.000000
    outer loop
      vertex 45.820480 -26.596506 15.000000
      vertex 46.020870 -27.099445 0.000000
      vertex 45.820480 -26.596506 0.000000
    endloop
  endfacet
  facet normal 0.963550 0.267528 0.000000
    outer loop
      vertex 45.675644 -26.074852 15.000000
      vertex 45.820480 -26.596506 15.000000
      vertex 45.820480 -26.596506 0.000000
    endloop
  endfacet
  facet normal 0.963550 0.267528 0.000000
    outer loop
      vertex 45.675644 -26.074852 15.000000
      vertex 45.820480 -26.596506 0.000000
      vertex 45.675644 -26.074852 0.000000
    endloop
  endfacet
  facet normal 0.986827 0.161780 0.000000
    outer loop
      vertex 45.588058 -25.540596 15.000000
      vertex 45.675644 -26.074852 15.000000
      vertex 45.675644 -26.074852 0.000000
    endloop
  endfacet
  facet normal 0.986827 0.161780 0.000000
    outer loop
      vertex 45.588058 -25.540596 15.000000
      vertex 45.675644 -26.074852 0.000000
      vertex 45.588058 -25.540596 0.000000
    endloop
  endfacet
  facet normal 0.998533 0.054142 0.000000
    outer loop
      vertex 45.558746 -25.000000 15.000000
      vertex 45.588058 -25.540596 15.000000
      vertex 45.588058 -25.540596 0.000000
    endloop
  endfacet
  facet normal 0.998533 0.054142 0.000000
    outer loop
      vertex 45.558746 -25.000000 15.000000
      vertex 45.588058 -25.540596 0.000000
      vertex 45.558746 -25.000000 0.000000
    endloop
  endfacet
  facet normal 0.998533 -0.054139 0.000000
    outer loop
      vertex -3.527667 60.432476 15.000000
      vertex -3.551116 60.000000 15.000000
      vertex -3.551116 60.000000 0.000000
    endloop
  endfacet
  facet normal 0.998533 -0.054139 0.000000
    outer loop
      vertex -3.527667 60.432476 15.000000
      vertex -3.551116 60.000000 0.000000
      vertex -3.527667 60.432476 0.000000
    endloop
  endfacet
  facet normal 0.986827 -0.161782 0.000000
    outer loop
      vertex -3.457598 60.859882 15.000000
      vertex -3.527667 60.432476 15.000000
      vertex -3.527667 60.432476 0.000000
    endloop
  endfacet
  facet normal 0.986827 -0.161782 0.000000
    outer loop
      vertex -3.457598 60.859882 15.000000
      vertex -3.527667 60.432476 0.000000
      vertex -3.457598 60.859882 0.000000
    endloop
  endfacet
  facet normal 0.963550 -0.267528 0.000000
    outer loop
      vertex -3.341728 61.277206 15.000000
      vertex -3.457598 60.859882 15.000000
      vertex -3.457598 60.859882 0.000000
    endloop
  endfacet
  facet normal 0.963550 -0.267528 0.000000
    outer loop
      vertex -3.341728 61.277206 15.000000
      vertex -3.457598 60.859882 0.000000
      vertex -3.341728 61.277206 0.000000
    endloop
  endfacet
  facet normal 0.928977 -0.370138 0.000000
    outer loop
      vertex -3.181417 61.679558 15.000000
      vertex -3.341728 61.277206 15.000000
      vertex -3.341728 61.277206 0.000000
    endloop
  endfacet
  facet normal 0.928977 -0.370138 0.000000
    outer loop
      vertex -3.181417 61.679558 15.000000
      vertex -3.341728 61.277206 0.000000
      vertex -3.181417 61.679558 0.000000
    endloop
  endfacet
  facet normal 0.883511 -0.468411 0.000000
    outer loop
      vertex -2.978544 62.062214 15.000000
      vertex -3.181417 61.679558 15.000000
      vertex -3.181417 61.679558 0.000000
    endloop
  endfacet
  facet normal 0.883511 -0.468411 0.000000
    outer loop
      vertex -2.978544 62.062214 15.000000
      vertex -3.181417 61.679558 0.000000
      vertex -2.978544 62.062214 0.000000
    endloop
  endfacet
  facet normal 0.827690 -0.561186 0.000000
    outer loop
      vertex -2.735488 62.420696 15.000000
      vertex -2.978544 62.062214 15.000000
      vertex -2.978544 62.062214 0.000000
    endloop
  endfacet
  facet normal 0.827690 -0.561186 0.000000
    outer loop
      vertex -2.735488 62.420696 15.000000
      vertex -2.978544 62.062214 0.000000
      vertex -2.735488 62.420696 0.000000
    endloop
  endfacet
  facet normal 0.762166 -0.647382 0.000000
    outer loop
      vertex -2.455098 62.750801 15.000000
      vertex -2.735488 62.420696 15.000000
      vertex -2.735488 62.420696 0.000000
    endloop
  endfacet
  facet normal 0.762166 -0.647382 0.000000
    outer loop
      vertex -2.455098 62.750801 15.000000
      vertex -2.735488 62.420696 0.000000
      vertex -2.455098 62.750801 0.000000
    endloop
  endfacet
  facet normal 0.687692 -0.726003 0.000000
    outer loop
      vertex -2.140661 63.048645 15.000000
      vertex -2.455098 62.750801 15.000000
      vertex -2.455098 62.750801 0.000000
    endloop
  endfacet
  facet normal 0.687692 -0.726003 0.000000
    outer loop
      vertex -2.140661 63.048645 15.000000
      vertex -2.455098 62.750801 0.000000
      vertex -2.140661 63.048645 0.000000
    endloop
  endfacet
  facet normal 0.605180 -0.796089 0.000000
    outer loop
      vertex -1.795864 63.310757 15.000000
      vertex -2.140661 63.048645 15.000000
      vertex -2.140661 63.048645 0.000000
    endloop
  endfacet
  facet normal 0.605180 -0.796089 0.000000
    outer loop
      vertex -1.795864 63.310757 15.000000
      vertex -2.140661 63.048645 0.000000
      vertex -1.795864 63.310757 0.000000
    endloop
  endfacet
  facet normal 0.515556 -0.856856 0.000000
    outer loop
      vertex -1.424749 63.534050 15.000000
      vertex -1.795864 63.310757 15.000000
      vertex -1.795864 63.310757 0.000000
    endloop
  endfacet
  facet normal 0.515556 -0.856856 0.000000
    outer loop
      vertex -1.424749 63.534050 15.000000
      vertex -1.795864 63.310757 0.000000
      vertex -1.424749 63.534050 0.000000
    endloop
  endfacet
  facet normal 0.419881 -0.907579 0.000000
    outer loop
      vertex -1.031668 63.715904 15.000000
      vertex -1.424749 63.534050 15.000000
      vertex -1.424749 63.534050 0.000000
    endloop
  endfacet
  facet normal 0.419881 -0.907579 0.000000
    outer loop
      vertex -1.031668 63.715904 15.000000
      vertex -1.424749 63.534050 0.000000
      vertex -1.031668 63.715904 0.000000
    endloop
  endfacet
  facet normal 0.319312 -0.947650 0.000000
    outer loop
      vertex -0.621229 63.854202 15.000000
      vertex -1.031668 63.715904 15.000000
      vertex -1.031668 63.715904 0.000000
    endloop
  endfacet
  facet normal 0.319312 -0.947650 0.000000
    outer loop
      vertex -0.621229 63.854202 15.000000
      vertex -1.031668 63.715904 0.000000
      vertex -0.621229 63.854202 0.000000
    endloop
  endfacet
  facet normal 0.214960 -0.976623 0.000000
    outer loop
      vertex -0.198244 63.947304 15.000000
      vertex -0.621229 63.854202 15.000000
      vertex -0.621229 63.854202 0.000000
    endloop
  endfacet
  facet normal 0.214960 -0.976623 0.000000
    outer loop
      vertex -0.198244 63.947304 15.000000
      vertex -0.621229 63.854202 0.000000
      vertex -0.198244 63.947304 0.000000
    endloop
  endfacet
  facet normal 0.108123 -0.994138 0.000000
    outer loop
      vertex 0.232329 63.994133 15.000000
      vertex -0.198244 63.947304 15.000000
      vertex -0.198244 63.947304 0.000000
    endloop
  endfacet
  facet normal 0.108123 -0.994138 0.000000
    outer loop
      vertex 0.232329 63.994133 15.000000
      vertex -0.198244 63.947304 0.000000
      vertex 0.232329 63.994133 0.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex 0.665440 63.994133 15.000000
      vertex 0.232329 63.994133 15.000000
      vertex 0.232329 63.994133 0.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex 0.665440 63.994133 15.000000
      vertex 0.232329 63.994133 0.000000
      vertex 0.665440 63.994133 0.000000
    endloop
  endfacet
  facet normal -0.108123 -0.994138 0.000000
    outer loop
      vertex 1.096012 63.947304 15.000000
      vertex 0.665440 63.994133 15.000000
      vertex 0.665440 63.994133 0.000000
    endloop
  endfacet
  facet normal -0.108123 -0.994138 -0.000000
    outer loop
      vertex 1.096012 63.947304 15.000000
      vertex 0.665440 63.994133 0.000000
      vertex 1.096012 63.947304 0.000000
    endloop
  endfacet
  facet normal -0.214960 -0.976623 0.000000
    outer loop
      vertex 1.518998 63.854202 15.000000
      vertex 1.096012 63.947304 15.000000
      vertex 1.096012 63.947304 0.000000
    endloop
  endfacet
  facet normal -0.214960 -0.976623 -0.000000
    outer loop
      vertex 1.518998 63.854202 15.000000
      vertex 1.096012 63.947304 0.000000
      vertex 1.518998 63.854202 0.000000
    endloop
  endfacet
  facet normal -0.319312 -0.947650 0.000000
    outer loop
      vertex 1.929437 63.715904 15.000000
      vertex 1.518998 63.854202 15.000000
      vertex 1.518998 63.854202 0.000000
    endloop
  endfacet
  facet normal -0.319312 -0.947650 -0.000000
    outer loop
      vertex 1.929437 63.715904 15.000000
      vertex 1.518998 63.854202 0.000000
      vertex 1.929437 63.715904 0.000000
    endloop
  endfacet
  facet normal -0.419880 -0.907579 0.000000
    outer loop
      vertex 2.322518 63.534050 15.000000
      vertex 1.929437 63.715904 15.000000
      vertex 1.929437 63.715904 0.000000
    endloop
  endfacet
  facet normal -0.419880 -0.907579 -0.000000
    outer loop
      vertex 2.322518 63.534050 15.000000
      vertex 1.929437 63.715904 0.000000
      vertex 2.322518 63.534050 0.000000
    endloop
  endfacet
  facet normal -0.515556 -0.856856 0.000000
    outer loop
      vertex 2.693633 63.310757 15.000000
      vertex 2.322518 63.534050 15.000000
      vertex 2.322518 63.534050 0.000000
    endloop
  endfacet
  facet normal -0.515556 -0.856856 -0.000000
    outer loop
      vertex 2.693633 63.310757 15.000000
      vertex 2.322518 63.534050 0.000000
      vertex 2.693633 63.310757 0.000000
    endloop
  endfacet
  facet normal -0.605180 -0.796089 0.000000
    outer loop
      vertex 3.038430 63.048645 15.000000
      vertex 2.693633 63.310757 15.000000
      vertex 2.693633 63.310757 0.000000
    endloop
  endfacet
  facet normal -0.605180 -0.796089 -0.000000
    outer loop
      vertex 3.038430 63.048645 15.000000
      vertex 2.693633 63.310757 0.000000
      vertex 3.038430 63.048645 0.000000
    endloop
  endfacet
  facet normal -0.687692 -0.726003 0.000000
    outer loop
      vertex 3.352866 62.750801 15.000000
      vertex 3.038430 63.048645 15.000000
      vertex 3.038430 63.048645 0.000000
    endloop
  endfacet
  facet normal -0.687692 -0.726003 -0.000000
    outer loop
      vertex 3.352866 62.750801 15.000000
      vertex 3.038430 63.048645 0.000000
      vertex 3.352866 62.750801 0.000000
    endloop
  endfacet
  facet normal -0.762166 -0.647382 0.000000
    outer loop
      vertex 3.633257 62.420696 15.000000
      vertex 3.352866 62.750801 15.000000
      vertex 3.352866 62.750801 0.000000
    endloop
  endfacet
  facet normal -0.762166 -0.647382 -0.000000
    outer loop
      vertex 3.633257 62.420696 15.000000
      vertex 3.352866 62.750801 0.000000
      vertex 3.633257 62.420696 0.000000
    endloop
  endfacet
  facet normal -0.827690 -0.561186 0.000000
    outer loop
      vertex 3.876313 62.062214 15.000000
      vertex 3.633257 62.420696 15.000000
      vertex 3.633257 62.420696 0.000000
    endloop
  endfacet
  facet normal -0.827690 -0.561186 -0.000000
    outer loop
      vertex 3.876313 62.062214 15.000000
      vertex 3.633257 62.420696 0.000000
      vertex 3.876313 62.062214 0.000000
    endloop
  endfacet
  facet normal -0.883511 -0.468411 0.000000
    outer loop
      vertex 4.079186 61.679558 15.000000
      vertex 3.876313 62.062214 15.000000
      vertex 3.876313 62.062214 0.000000
    endloop
  endfacet
  facet normal -0.883511 -0.468411 -0.000000
    outer loop
      vertex 4.079186 61.679558 15.000000
      vertex 3.876313 62.062214 0.000000
      vertex 4.079186 61.679558 0.000000
    endloop
  endfacet
  facet normal -0.928977 -0.370138 0.000000
    outer loop
      vertex 4.239497 61.277206 15.000000
      vertex 4.079186 61.679558 15.000000
      vertex 4.079186 61.679558 0.000000
    endloop
  endfacet
  facet normal -0.928977 -0.370138 -0.000000
    outer loop
      vertex 4.239497 61.277206 15.000000
      vertex 4.079186 61.679558 0.000000
      vertex 4.239497 61.277206 0.000000
    endloop
  endfacet
  facet normal -0.963550 -0.267528 0.000000
    outer loop
      vertex 4.355367 60.859882 15.000000
      vertex 4.239497 61.277206 15.000000
      vertex 4.239497 61.277206 0.000000
    endloop
  endfacet
  facet normal -0.963550 -0.267528 -0.000000
    outer loop
      vertex 4.355367 60.859882 15.000000
      vertex 4.239497 61.277206 0.000000
      vertex 4.355367 60.859882 0.000000
    endloop
  endfacet
  facet normal -0.986827 -0.161781 0.000000
    outer loop
      vertex 4.425436 60.432476 15.000000
      vertex 4.355367 60.859882 15.000000
      vertex 4.355367 60.859882 0.000000
    endloop
  endfacet
  facet normal -0.986827 -0.161781 -0.000000
    outer loop
      vertex 4.425436 60.432476 15.000000
      vertex 4.355367 60.859882 0.000000
      vertex 4.425436 60.432476 0.000000
    endloop
  endfacet
  facet normal -0.998533 -0.054140 0.000000
    outer loop
      vertex 4.448884 60.000000 15.000000
      vertex 4.425436 60.432476 15.000000
      vertex 4.425436 60.432476 0.000000
    endloop
  endfacet
  facet normal -0.998533 -0.054140 -0.000000
    outer loop
      vertex 4.448884 60.000000 15.000000
      vertex 4.425436 60.432476 0.000000
      vertex 4.448884 60.000000 0.000000
    endloop
  endfacet
  facet normal -0.998533 0.054140 0.000000
    outer loop
      vertex 4.425436 59.567524 15.000000
      vertex 4.448884 60.000000 15.000000
      vertex 4.448884 60.000000 0.000000
    endloop
  endfacet
  facet normal -0.998533 0.054140 0.000000
    outer loop
      vertex 4.425436 59.567524 15.000000
      vertex 4.448884 60.000000 0.000000
      vertex 4.425436 59.567524 0.000000
    endloop
  endfacet
  facet normal -0.986826 0.161783 0.000000
    outer loop
      vertex 4.355367 59.140121 15.000000
      vertex 4.425436 59.567524 15.000000
      vertex 4.425436 59.567524 0.000000
    endloop
  endfacet
  facet normal -0.986826 0.161783 0.000000
    outer loop
      vertex 4.355367 59.140121 15.000000
      vertex 4.425436 59.567524 0.000000
      vertex 4.355367 59.140121 0.000000
    endloop
  endfacet
  facet normal -0.963551 0.267526 0.000000
    outer loop
      vertex 4.239497 58.722794 15.000000
      vertex 4.355367 59.140121 15.000000
      vertex 4.355367 59.140121 0.000000
    endloop
  endfacet
  facet normal -0.963551 0.267526 0.000000
    outer loop
      vertex 4.239497 58.722794 15.000000
      vertex 4.355367 59.140121 0.000000
      vertex 4.239497 58.722794 0.000000
    endloop
  endfacet
  facet normal -0.928977 0.370138 0.000000
    outer loop
      vertex 4.079186 58.320442 15.000000
      vertex 4.239497 58.722794 15.000000
      vertex 4.239497 58.722794 0.000000
    endloop
  endfacet
  facet normal -0.928977 0.370138 0.000000
    outer loop
      vertex 4.079186 58.320442 15.000000
      vertex 4.239497 58.722794 0.000000
      vertex 4.079186 58.320442 0.000000
    endloop
  endfacet
  facet normal -0.883511 0.468411 0.000000
    outer loop
      vertex 3.876313 57.937786 15.000000
      vertex 4.079186 58.320442 15.000000
      vertex 4.079186 58.320442 0.000000
    endloop
  endfacet
  facet normal -0.883511 0.468411 0.000000
    outer loop
      vertex 3.876313 57.937786 15.000000
      vertex 4.079186 58.320442 0.000000
      vertex 3.876313 57.937786 0.000000
    endloop
  endfacet
  facet normal -0.827692 0.561182 0.000000
    outer loop
      vertex 3.633257 57.579300 15.000000
      vertex 3.876313 57.937786 15.000000
      vertex 3.876313 57.937786 0.000000
    endloop
  endfacet
  facet normal -0.827692 0.561182 0.000000
    outer loop
      vertex 3.633257 57.579300 15.000000
      vertex 3.876313 57.937786 0.000000
      vertex 3.633257 57.579300 0.000000
    endloop
  endfacet
  facet normal -0.762158 0.647391 0.000000
    outer loop
      vertex 3.352866 57.249203 15.000000
      vertex 3.633257 57.579300 15.000000
      vertex 3.633257 57.579300 0.000000
    endloop
  endfacet
  facet normal -0.762158 0.647391 0.000000
    outer loop
      vertex 3.352866 57.249203 15.000000
      vertex 3.633257 57.579300 0.000000
      vertex 3.352866 57.249203 0.000000
    endloop
  endfacet
  facet normal -0.687701 0.725994 0.000000
    outer loop
      vertex 3.038430 56.951351 15.000000
      vertex 3.352866 57.249203 15.000000
      vertex 3.352866 57.249203 0.000000
    endloop
  endfacet
  facet normal -0.687701 0.725994 0.000000
    outer loop
      vertex 3.038430 56.951351 15.000000
      vertex 3.352866 57.249203 0.000000
      vertex 3.038430 56.951351 0.000000
    endloop
  endfacet
  facet normal -0.605174 0.796093 0.000000
    outer loop
      vertex 2.693633 56.689243 15.000000
      vertex 3.038430 56.951351 15.000000
      vertex 3.038430 56.951351 0.000000
    endloop
  endfacet
  facet normal -0.605174 0.796093 0.000000
    outer loop
      vertex 2.693633 56.689243 15.000000
      vertex 3.038430 56.951351 0.000000
      vertex 2.693633 56.689243 0.000000
    endloop
  endfacet
  facet normal -0.515550 0.856860 0.000000
    outer loop
      vertex 2.322518 56.465954 15.000000
      vertex 2.693633 56.689243 15.000000
      vertex 2.693633 56.689243 0.000000
    endloop
  endfacet
  facet normal -0.515550 0.856860 0.000000
    outer loop
      vertex 2.322518 56.465954 15.000000
      vertex 2.693633 56.689243 0.000000
      vertex 2.322518 56.465954 0.000000
    endloop
  endfacet
  facet normal -0.419895 0.907573 0.000000
    outer loop
      vertex 1.929437 56.284092 15.000000
      vertex 2.322518 56.465954 15.000000
      vertex 2.322518 56.465954 0.000000
    endloop
  endfacet
  facet normal -0.419895 0.907573 0.000000
    outer loop
      vertex 1.929437 56.284092 15.000000
      vertex 2.322518 56.465954 0.000000
      vertex 1.929437 56.284092 0.000000
    endloop
  endfacet
  facet normal -0.319304 0.947652 0.000000
    outer loop
      vertex 1.518998 56.145798 15.000000
      vertex 1.929437 56.284092 15.000000
      vertex 1.929437 56.284092 0.000000
    endloop
  endfacet
  facet normal -0.319304 0.947652 0.000000
    outer loop
      vertex 1.518998 56.145798 15.000000
      vertex 1.929437 56.284092 0.000000
      vertex 1.518998 56.145798 0.000000
    endloop
  endfacet
  facet normal -0.214969 0.976621 0.000000
    outer loop
      vertex 1.096012 56.052692 15.000000
      vertex 1.518998 56.145798 15.000000
      vertex 1.518998 56.145798 0.000000
    endloop
  endfacet
  facet normal -0.214969 0.976621 0.000000
    outer loop
      vertex 1.096012 56.052692 15.000000
      vertex 1.518998 56.145798 0.000000
      vertex 1.096012 56.052692 0.000000
    endloop
  endfacet
  facet normal -0.108114 0.994138 0.000000
    outer loop
      vertex 0.665440 56.005867 15.000000
      vertex 1.096012 56.052692 15.000000
      vertex 1.096012 56.052692 0.000000
    endloop
  endfacet
  facet normal -0.108114 0.994138 0.000000
    outer loop
      vertex 0.665440 56.005867 15.000000
      vertex 1.096012 56.052692 0.000000
      vertex 0.665440 56.005867 0.000000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 0.232329 56.005867 15.000000
      vertex 0.665440 56.005867 15.000000
      vertex 0.665440 56.005867 0.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 0.232329 56.005867 15.000000
      vertex 0.665440 56.005867 0.000000
      vertex 0.232329 56.005867 0.000000
    endloop
  endfacet
  facet normal 0.108114 0.994138 0.000000
    outer loop
      vertex -0.198244 56.052692 15.000000
      vertex 0.232329 56.005867 15.000000
      vertex 0.232329 56.005867 0.000000
    endloop
  endfacet
  facet normal 0.108114 0.994138 0.000000
    outer loop
      vertex -0.198244 56.052692 15.000000
      vertex 0.232329 56.005867 0.000000
      vertex -0.198244 56.052692 0.000000
    endloop
  endfacet
  facet normal 0.214969 0.976621 0.000000
    outer loop
      vertex -0.621229 56.145798 15.000000
      vertex -0.198244 56.052692 15.000000
      vertex -0.198244 56.052692 0.000000
    endloop
  endfacet
  facet normal 0.214969 0.976621 0.000000
    outer loop
      vertex -0.621229 56.145798 15.000000
      vertex -0.198244 56.052692 0.000000
      vertex -0.621229 56.145798 0.000000
    endloop
  endfacet
  facet normal 0.319304 0.947652 0.000000
    outer loop
      vertex -1.031668 56.284092 15.000000
      vertex -0.621229 56.145798 15.000000
      vertex -0.621229 56.145798 0.000000
    endloop
  endfacet
  facet normal 0.319304 0.947652 0.000000
    outer loop
      vertex -1.031668 56.284092 15.000000
      vertex -0.621229 56.145798 0.000000
      vertex -1.031668 56.284092 0.000000
    endloop
  endfacet
  facet normal 0.419895 0.907573 0.000000
    outer loop
      vertex -1.424749 56.465954 15.000000
      vertex -1.031668 56.284092 15.000000
      vertex -1.031668 56.284092 0.000000
    endloop
  endfacet
  facet normal 0.419895 0.907573 0.000000
    outer loop
      vertex -1.424749 56.465954 15.000000
      vertex -1.031668 56.284092 0.000000
      vertex -1.424749 56.465954 0.000000
    endloop
  endfacet
  facet normal 0.515549 0.856860 0.000000
    outer loop
      vertex -1.795864 56.689243 15.000000
      vertex -1.424749 56.465954 15.000000
      vertex -1.424749 56.465954 0.000000
    endloop
  endfacet
  facet normal 0.515549 0.856860 0.000000
    outer loop
      vertex -1.795864 56.689243 15.000000
      vertex -1.424749 56.465954 0.000000
      vertex -1.795864 56.689243 0.000000
    endloop
  endfacet
  facet normal 0.605174 0.796093 0.000000
    outer loop
      vertex -2.140661 56.951351 15.000000
      vertex -1.795864 56.689243 15.000000
      vertex -1.795864 56.689243 0.000000
    endloop
  endfacet
  facet normal 0.605174 0.796093 0.000000
    outer loop
      vertex -2.140661 56.951351 15.000000
      vertex -1.795864 56.689243 0.000000
      vertex -2.140661 56.951351 0.000000
    endloop
  endfacet
  facet normal 0.687701 0.725994 0.000000
    outer loop
      vertex -2.455098 57.249203 15.000000
      vertex -2.140661 56.951351 15.000000
      vertex -2.140661 56.951351 0.000000
    endloop
  endfacet
  facet normal 0.687701 0.725994 0.000000
    outer loop
      vertex -2.455098 57.249203 15.000000
      vertex -2.140661 56.951351 0.000000
      vertex -2.455098 57.249203 0.000000
    endloop
  endfacet
  facet normal 0.762158 0.647391 0.000000
    outer loop
      vertex -2.735488 57.579300 15.000000
      vertex -2.455098 57.249203 15.000000
      vertex -2.455098 57.249203 0.000000
    endloop
  endfacet
  facet normal 0.762158 0.647391 0.000000
    outer loop
      vertex -2.735488 57.579300 15.000000
      vertex -2.455098 57.249203 0.000000
      vertex -2.735488 57.579300 0.000000
    endloop
  endfacet
  facet normal 0.827693 0.561182 0.000000
    outer loop
      vertex -2.978544 57.937786 15.000000
      vertex -2.735488 57.579300 15.000000
      vertex -2.735488 57.579300 0.000000
    endloop
  endfacet
  facet normal 0.827693 0.561182 0.000000
    outer loop
      vertex -2.978544 57.937786 15.000000
      vertex -2.735488 57.579300 0.000000
      vertex -2.978544 57.937786 0.000000
    endloop
  endfacet
  facet normal 0.883511 0.468411 0.000000
    outer loop
      vertex -3.181417 58.320442 15.000000
      vertex -2.978544 57.937786 15.000000
      vertex -2.978544 57.937786 0.000000
    endloop
  endfacet
  facet normal 0.883511 0.468411 0.000000
    outer loop
      vertex -3.181417 58.320442 15.000000
      vertex -2.978544 57.937786 0.000000
      vertex -3.181417 58.320442 0.000000
    endloop
  endfacet
  facet normal 0.928977 0.370138 0.000000
    outer loop
      vertex -3.341728 58.722794 15.000000
      vertex -3.181417 58.320442 15.000000
      vertex -3.181417 58.320442 0.000000
    endloop
  endfacet
  facet normal 0.928977 0.370138 0.000000
    outer loop
      vertex -3.341728 58.722794 15.000000
      vertex -3.181417 58.320442 0.000000
      vertex -3.341728 58.722794 0.000000
    endloop
  endfacet
  facet normal 0.963551 0.267526 0.000000
    outer loop
      vertex -3.457598 59.140121 15.000000
      vertex -3.341728 58.722794 15.000000
      vertex -3.341728 58.722794 0.000000
    endloop
  endfacet
  facet normal 0.963551 0.267526 0.000000
    outer loop
      vertex -3.457598 59.140121 15.000000
      vertex -3.341728 58.722794 0.000000
      vertex -3.457598 59.140121 0.000000
    endloop
  endfacet
  facet normal 0.986826 0.161783 0.000000
    outer loop
      vertex -3.527667 59.567524 15.000000
      vertex -3.457598 59.140121 15.000000
      vertex -3.457598 59.140121 0.000000
    endloop
  endfacet
  facet normal 0.986826 0.161783 0.000000
    outer loop
      vertex -3.527667 59.567524 15.000000
      vertex -3.457598 59.140121 0.000000
      vertex -3.527667 59.567524 0.000000
    endloop
  endfacet
  facet normal 0.998533 0.054139 0.000000
    outer loop
      vertex -3.551116 60.000000 15.000000
      vertex -3.527667 59.567524 15.000000
      vertex -3.527667 59.567524 0.000000
    endloop
  endfacet
  facet normal 0.998533 0.054139 0.000000
    outer loop
      vertex -3.551116 60.000000 15.000000
      vertex -3.527667 59.567524 0.000000
      vertex -3.551116 60.000000 0.000000
    endloop
  endfacet
  facet normal -0.992948 -0.118549 0.000000
    outer loop
      vertex -98.257126 -1.138039 0.000000
      vertex -98.392998 -0.000000 15.000000
      vertex -98.392998 -0.000000 0.000000
    endloop
  endfacet
  facet normal -0.992948 -0.118549 -0.000000
    outer loop
      vertex -98.257126 -1.138039 15.000000
      vertex -98.392998 -0.000000 15.000000
      vertex -98.257126 -1.138039 0.000000
    endloop
  endfacet
  facet normal -0.974310 -0.225210 -0.000000
    outer loop
      vertex -98.257126 -1.138039 15.000000
      vertex -98.257126 -1.138039 0.000000
      vertex -97.999008 -2.254716 0.000000
    endloop
  endfacet
  facet normal -0.974310 -0.225210 -0.000000
    outer loop
      vertex -97.999008 -2.254716 15.000000
      vertex -98.257126 -1.138039 15.000000
      vertex -97.999008 -2.254716 0.000000
    endloop
  endfacet
  facet normal -0.944248 -0.329234 -0.000000
    outer loop
      vertex -97.999008 -2.254716 15.000000
      vertex -97.999008 -2.254716 0.000000
      vertex -97.621666 -3.336940 0.000000
    endloop
  endfacet
  facet normal -0.944248 -0.329234 -0.000000
    outer loop
      vertex -97.621666 -3.336940 15.000000
      vertex -97.999008 -2.254716 15.000000
      vertex -97.621666 -3.336940 0.000000
    endloop
  endfacet
  facet normal -0.903118 -0.429392 -0.000000
    outer loop
      vertex -97.621666 -3.336940 15.000000
      vertex -97.621666 -3.336940 0.000000
      vertex -97.129532 -4.372022 0.000000
    endloop
  endfacet
  facet normal -0.903118 -0.429392 -0.000000
    outer loop
      vertex -97.129532 -4.372022 15.000000
      vertex -97.621666 -3.336940 15.000000
      vertex -97.129532 -4.372022 0.000000
    endloop
  endfacet
  facet normal -0.851397 -0.524522 -0.000000
    outer loop
      vertex -97.129532 -4.372022 15.000000
      vertex -97.129532 -4.372022 0.000000
      vertex -96.528366 -5.347826 0.000000
    endloop
  endfacet
  facet normal -0.851397 -0.524522 -0.000000
    outer loop
      vertex -96.528366 -5.347826 15.000000
      vertex -97.129532 -4.372022 15.000000
      vertex -96.528366 -5.347826 0.000000
    endloop
  endfacet
  facet normal -0.789694 -0.613501 -0.000000
    outer loop
      vertex -96.528366 -5.347826 15.000000
      vertex -96.528366 -5.347826 0.000000
      vertex -95.825218 -6.252914 0.000000
    endloop
  endfacet
  facet normal -0.789694 -0.613501 -0.000000
    outer loop
      vertex -95.825218 -6.252914 15.000000
      vertex -96.528366 -5.347826 15.000000
      vertex -95.825218 -6.252914 0.000000
    endloop
  endfacet
  facet normal -0.718737 -0.695282 -0.000000
    outer loop
      vertex -95.825218 -6.252914 15.000000
      vertex -95.825218 -6.252914 0.000000
      vertex -95.028343 -7.076672 0.000000
    endloop
  endfacet
  facet normal -0.718737 -0.695282 -0.000000
    outer loop
      vertex -95.028343 -7.076672 15.000000
      vertex -95.825218 -6.252914 15.000000
      vertex -95.028343 -7.076672 0.000000
    endloop
  endfacet
  facet normal -0.639349 -0.768916 -0.000000
    outer loop
      vertex -95.028343 -7.076672 15.000000
      vertex -95.028343 -7.076672 0.000000
      vertex -94.147072 -7.809444 0.000000
    endloop
  endfacet
  facet normal -0.639349 -0.768916 -0.000000
    outer loop
      vertex -94.147072 -7.809444 15.000000
      vertex -95.028343 -7.076672 15.000000
      vertex -94.147072 -7.809444 0.000000
    endloop
  endfacet
  facet normal -0.552464 -0.833537 -0.000000
    outer loop
      vertex -94.147072 -7.809444 15.000000
      vertex -94.147072 -7.809444 0.000000
      vertex -93.191734 -8.442637 0.000000
    endloop
  endfacet
  facet normal -0.552464 -0.833537 -0.000000
    outer loop
      vertex -93.191734 -8.442637 15.000000
      vertex -94.147072 -7.809444 15.000000
      vertex -93.191734 -8.442637 0.000000
    endloop
  endfacet
  facet normal -0.459109 -0.888380 -0.000000
    outer loop
      vertex -93.191734 -8.442637 15.000000
      vertex -93.191734 -8.442637 0.000000
      vertex -92.173546 -8.968830 0.000000
    endloop
  endfacet
  facet normal -0.459109 -0.888380 -0.000000
    outer loop
      vertex -92.173546 -8.968830 15.000000
      vertex -93.191734 -8.442637 15.000000
      vertex -92.173546 -8.968830 0.000000
    endloop
  endfacet
  facet normal -0.360365 -0.932811 -0.000000
    outer loop
      vertex -92.173546 -8.968830 15.000000
      vertex -92.173546 -8.968830 0.000000
      vertex -91.104431 -9.381852 0.000000
    endloop
  endfacet
  facet normal -0.360365 -0.932811 -0.000000
    outer loop
      vertex -91.104431 -9.381852 15.000000
      vertex -92.173546 -8.968830 15.000000
      vertex -91.104431 -9.381852 0.000000
    endloop
  endfacet
  facet normal -0.257397 -0.966306 -0.000000
    outer loop
      vertex -91.104431 -9.381852 15.000000
      vertex -91.104431 -9.381852 0.000000
      vertex -89.996925 -9.676861 0.000000
    endloop
  endfacet
  facet normal -0.257397 -0.966306 -0.000000
    outer loop
      vertex -89.996925 -9.676861 15.000000
      vertex -91.104431 -9.381852 15.000000
      vertex -89.996925 -9.676861 0.000000
    endloop
  endfacet
  facet normal -0.151414 -0.988470 -0.000000
    outer loop
      vertex -89.996925 -9.676861 15.000000
      vertex -89.996925 -9.676861 0.000000
      vertex -88.864021 -9.850399 0.000000
    endloop
  endfacet
  facet normal -0.151414 -0.988470 -0.000000
    outer loop
      vertex -88.864021 -9.850399 15.000000
      vertex -89.996925 -9.676861 15.000000
      vertex -88.864021 -9.850399 0.000000
    endloop
  endfacet
  facet normal -0.043653 -0.999047 -0.000000
    outer loop
      vertex -88.864021 -9.850399 15.000000
      vertex -88.864021 -9.850399 0.000000
      vertex -87.718994 -9.900431 0.000000
    endloop
  endfacet
  facet normal -0.043653 -0.999047 -0.000000
    outer loop
      vertex -87.718994 -9.900431 15.000000
      vertex -88.864021 -9.850399 15.000000
      vertex -87.718994 -9.900431 0.000000
    endloop
  endfacet
  facet normal 0.064620 -0.997910 0.000000
    outer loop
      vertex -87.718994 -9.900431 15.000000
      vertex -87.718994 -9.900431 0.000000
      vertex -86.575264 -9.826368 0.000000
    endloop
  endfacet
  facet normal 0.064620 -0.997910 0.000000
    outer loop
      vertex -86.575264 -9.826368 15.000000
      vertex -87.718994 -9.900431 15.000000
      vertex -86.575264 -9.826368 0.000000
    endloop
  endfacet
  facet normal 0.172133 -0.985074 0.000000
    outer loop
      vertex -86.575264 -9.826368 15.000000
      vertex -86.575264 -9.826368 0.000000
      vertex -85.446251 -9.629083 0.000000
    endloop
  endfacet
  facet normal 0.172133 -0.985074 0.000000
    outer loop
      vertex -85.446251 -9.629083 15.000000
      vertex -86.575264 -9.826368 15.000000
      vertex -85.446251 -9.629083 0.000000
    endloop
  endfacet
  facet normal 0.277629 -0.960689 0.000000
    outer loop
      vertex -85.446251 -9.629083 15.000000
      vertex -85.446251 -9.629083 0.000000
      vertex -84.345184 -9.310886 0.000000
    endloop
  endfacet
  facet normal 0.277629 -0.960689 0.000000
    outer loop
      vertex -84.345184 -9.310886 15.000000
      vertex -85.446251 -9.629083 15.000000
      vertex -84.345184 -9.310886 0.000000
    endloop
  endfacet
  facet normal 0.379871 -0.925039 0.000000
    outer loop
      vertex -84.345184 -9.310886 15.000000
      vertex -84.345184 -9.310886 0.000000
      vertex -83.284981 -8.875509 0.000000
    endloop
  endfacet
  facet normal 0.379871 -0.925039 0.000000
    outer loop
      vertex -83.284981 -8.875509 15.000000
      vertex -84.345184 -9.310886 15.000000
      vertex -83.284981 -8.875509 0.000000
    endloop
  endfacet
  facet normal 0.477659 -0.878546 0.000000
    outer loop
      vertex -83.284981 -8.875509 15.000000
      vertex -83.284981 -8.875509 0.000000
      vertex -82.278061 -8.328054 0.000000
    endloop
  endfacet
  facet normal 0.477659 -0.878546 0.000000
    outer loop
      vertex -82.278061 -8.328054 15.000000
      vertex -83.284981 -8.875509 15.000000
      vertex -82.278061 -8.328054 0.000000
    endloop
  endfacet
  facet normal 0.569843 -0.821754 0.000000
    outer loop
      vertex -82.278061 -8.328054 15.000000
      vertex -82.278061 -8.328054 0.000000
      vertex -81.336227 -7.674942 0.000000
    endloop
  endfacet
  facet normal 0.569843 -0.821754 0.000000
    outer loop
      vertex -81.336227 -7.674942 15.000000
      vertex -82.278061 -8.328054 15.000000
      vertex -81.336227 -7.674942 0.000000
    endloop
  endfacet
  facet normal 0.655356 -0.755320 0.000000
    outer loop
      vertex -81.336227 -7.674942 15.000000
      vertex -81.336227 -7.674942 0.000000
      vertex -80.470543 -6.923829 0.000000
    endloop
  endfacet
  facet normal 0.655356 -0.755320 0.000000
    outer loop
      vertex -80.470543 -6.923829 15.000000
      vertex -81.336227 -7.674942 15.000000
      vertex -80.470543 -6.923829 0.000000
    endloop
  endfacet
  facet normal 0.733171 -0.680045 0.000000
    outer loop
      vertex -80.470543 -6.923829 15.000000
      vertex -80.470543 -6.923829 0.000000
      vertex -79.691124 -6.083521 0.000000
    endloop
  endfacet
  facet normal 0.733171 -0.680045 0.000000
    outer loop
      vertex -79.691124 -6.083521 15.000000
      vertex -80.470543 -6.923829 15.000000
      vertex -79.691124 -6.083521 0.000000
    endloop
  endfacet
  facet normal 0.802404 -0.596781 0.000000
    outer loop
      vertex -79.691124 -6.083521 15.000000
      vertex -79.691124 -6.083521 0.000000
      vertex -79.007141 -5.163870 0.000000
    endloop
  endfacet
  facet normal 0.802404 -0.596781 0.000000
    outer loop
      vertex -79.007141 -5.163870 15.000000
      vertex -79.691124 -6.083521 15.000000
      vertex -79.007141 -5.163870 0.000000
    endloop
  endfacet
  facet normal 0.862223 -0.506529 0.000000
    outer loop
      vertex -79.007141 -5.163870 15.000000
      vertex -79.007141 -5.163870 0.000000
      vertex -78.426598 -4.175659 0.000000
    endloop
  endfacet
  facet normal 0.862223 -0.506529 0.000000
    outer loop
      vertex -78.426598 -4.175659 15.000000
      vertex -79.007141 -5.163870 15.000000
      vertex -78.426598 -4.175659 0.000000
    endloop
  endfacet
  facet normal 0.911935 -0.410334 0.000000
    outer loop
      vertex -78.426598 -4.175659 15.000000
      vertex -78.426598 -4.175659 0.000000
      vertex -77.956306 -3.130472 0.000000
    endloop
  endfacet
  facet normal 0.911935 -0.410334 0.000000
    outer loop
      vertex -77.956306 -3.130472 15.000000
      vertex -78.426598 -4.175659 15.000000
      vertex -77.956306 -3.130472 0.000000
    endloop
  endfacet
  facet normal 0.950953 -0.309337 0.000000
    outer loop
      vertex -77.956306 -3.130472 15.000000
      vertex -77.956306 -3.130472 0.000000
      vertex -77.601768 -2.040565 0.000000
    endloop
  endfacet
  facet normal 0.950953 -0.309337 0.000000
    outer loop
      vertex -77.601768 -2.040565 15.000000
      vertex -77.956306 -3.130472 15.000000
      vertex -77.601768 -2.040565 0.000000
    endloop
  endfacet
  facet normal 0.978823 -0.204707 0.000000
    outer loop
      vertex -77.601768 -2.040565 15.000000
      vertex -77.601768 -2.040565 0.000000
      vertex -77.367149 -0.918714 0.000000
    endloop
  endfacet
  facet normal 0.978823 -0.204707 0.000000
    outer loop
      vertex -77.367149 -0.918714 15.000000
      vertex -77.601768 -2.040565 15.000000
      vertex -77.367149 -0.918714 0.000000
    endloop
  endfacet
  facet normal 0.995219 -0.097674 0.000000
    outer loop
      vertex -77.367149 -0.918714 15.000000
      vertex -77.367149 -0.918714 0.000000
      vertex -77.255203 0.221927 0.000000
    endloop
  endfacet
  facet normal 0.995219 -0.097674 0.000000
    outer loop
      vertex -77.255203 0.221927 15.000000
      vertex -77.367149 -0.918714 15.000000
      vertex -77.255203 0.221927 0.000000
    endloop
  endfacet
  facet normal 0.999945 0.010498 0.000000
    outer loop
      vertex -77.255203 0.221927 15.000000
      vertex -77.255203 0.221927 0.000000
      vertex -77.267235 1.367985 0.000000
    endloop
  endfacet
  facet normal 0.999945 0.010498 0.000000
    outer loop
      vertex -77.267235 1.367985 15.000000
      vertex -77.255203 0.221927 15.000000
      vertex -77.267235 1.367985 0.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex -98.392998 30.000000 0.000000
      vertex -98.392998 -0.000000 0.000000
      vertex -98.392998 -0.000000 15.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex -98.392998 30.000000 0.000000
      vertex -98.392998 -0.000000 15.000000
      vertex -98.392998 30.000000 15.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex -98.392998 61.323826 0.000000
      vertex -98.392998 30.000000 0.000000
      vertex -98.392998 30.000000 15.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex -98.392998 61.323826 0.000000
      vertex -98.392998 30.000000 15.000000
      vertex -98.392998 61.323826 15.000000
    endloop
  endfacet
  facet normal -0.428000 0.903779 0.000000
    outer loop
      vertex -87.038231 80.379112 0.000000
      vertex -84.934654 81.375298 15.000000
      vertex -84.934654 81.375298 0.000000
    endloop
  endfacet
  facet normal -0.428000 0.903779 0.000000
    outer loop
      vertex -87.038231 80.379112 15.000000
      vertex -84.934654 81.375298 15.000000
      vertex -87.038231 80.379112 0.000000
    endloop
  endfacet
  facet normal -0.522482 0.852650 0.000000
    outer loop
      vertex -87.038231 80.379112 15.000000
      vertex -87.038231 80.379112 0.000000
      vertex -89.022804 79.163017 0.000000
    endloop
  endfacet
  facet normal -0.522482 0.852650 0.000000
    outer loop
      vertex -89.022804 79.163017 15.000000
      vertex -87.038231 80.379112 15.000000
      vertex -89.022804 79.163017 0.000000
    endloop
  endfacet
  facet normal -0.610928 0.791686 0.000000
    outer loop
      vertex -89.022804 79.163017 15.000000
      vertex -89.022804 79.163017 0.000000
      vertex -90.865486 77.741058 0.000000
    endloop
  endfacet
  facet normal -0.610928 0.791686 0.000000
    outer loop
      vertex -90.865486 77.741058 15.000000
      vertex -89.022804 79.163017 15.000000
      vertex -90.865486 77.741058 0.000000
    endloop
  endfacet
  facet normal -0.692331 0.721580 0.000000
    outer loop
      vertex -90.865486 77.741058 15.000000
      vertex -90.865486 77.741058 0.000000
      vertex -92.544991 76.129631 0.000000
    endloop
  endfacet
  facet normal -0.692331 0.721580 0.000000
    outer loop
      vertex -92.544991 76.129631 15.000000
      vertex -90.865486 77.741058 15.000000
      vertex -92.544991 76.129631 0.000000
    endloop
  endfacet
  facet normal -0.765740 0.643151 0.000000
    outer loop
      vertex -92.544991 76.129631 15.000000
      vertex -92.544991 76.129631 0.000000
      vertex -94.041954 74.347336 0.000000
    endloop
  endfacet
  facet normal -0.765740 0.643151 0.000000
    outer loop
      vertex -94.041954 74.347336 15.000000
      vertex -92.544991 76.129631 15.000000
      vertex -94.041954 74.347336 0.000000
    endloop
  endfacet
  facet normal -0.830313 0.557297 0.000000
    outer loop
      vertex -94.041954 74.347336 15.000000
      vertex -94.041954 74.347336 0.000000
      vertex -95.339081 72.414757 0.000000
    endloop
  endfacet
  facet normal -0.830313 0.557297 0.000000
    outer loop
      vertex -95.339081 72.414757 15.000000
      vertex -94.041954 74.347336 15.000000
      vertex -95.339081 72.414757 0.000000
    endloop
  endfacet
  facet normal -0.885303 0.465013 0.000000
    outer loop
      vertex -95.339081 72.414757 15.000000
      vertex -95.339081 72.414757 0.000000
      vertex -96.421417 70.354179 0.000000
    endloop
  endfacet
  facet normal -0.885303 0.465013 0.000000
    outer loop
      vertex -96.421417 70.354179 15.000000
      vertex -95.339081 72.414757 15.000000
      vertex -96.421417 70.354179 0.000000
    endloop
  endfacet
  facet normal -0.930077 0.367364 0.000000
    outer loop
      vertex -96.421417 70.354179 15.000000
      vertex -96.421417 70.354179 0.000000
      vertex -97.276474 68.189384 0.000000
    endloop
  endfacet
  facet normal -0.930077 0.367364 0.000000
    outer loop
      vertex -97.276474 68.189384 15.000000
      vertex -96.421417 70.354179 15.000000
      vertex -97.276474 68.189384 0.000000
    endloop
  endfacet
  facet normal -0.964118 0.265473 0.000000
    outer loop
      vertex -97.276474 68.189384 15.000000
      vertex -97.276474 68.189384 0.000000
      vertex -97.894371 65.945366 0.000000
    endloop
  endfacet
  facet normal -0.964118 0.265473 0.000000
    outer loop
      vertex -97.894371 65.945366 15.000000
      vertex -97.276474 68.189384 15.000000
      vertex -97.894371 65.945366 0.000000
    endloop
  endfacet
  facet normal -0.987033 0.160518 0.000000
    outer loop
      vertex -97.894371 65.945366 15.000000
      vertex -97.894371 65.945366 0.000000
      vertex -98.267982 63.648006 0.000000
    endloop
  endfacet
  facet normal -0.987033 0.160518 0.000000
    outer loop
      vertex -98.267982 63.648006 15.000000
      vertex -97.894371 65.945366 15.000000
      vertex -98.267982 63.648006 0.000000
    endloop
  endfacet
  facet normal -0.998557 0.053711 0.000000
    outer loop
      vertex -98.267982 63.648006 15.000000
      vertex -98.267982 63.648006 0.000000
      vertex -98.392998 61.323826 0.000000
    endloop
  endfacet
  facet normal -0.998557 0.053711 0.000000
    outer loop
      vertex -98.392998 61.323826 15.000000
      vertex -98.267982 63.648006 15.000000
      vertex -98.392998 61.323826 0.000000
    endloop
  endfacet
  facet normal -0.115084 0.993356 0.000000
    outer loop
      vertex 25.003807 94.112053 15.000000
      vertex 49.600864 96.961708 15.000000
      vertex 49.600864 96.961708 0.000000
    endloop
  endfacet
  facet normal -0.115084 0.993356 0.000000
    outer loop
      vertex 25.003807 94.112053 15.000000
      vertex 49.600864 96.961708 0.000000
      vertex 25.003807 94.112053 0.000000
    endloop
  endfacet
  facet normal -0.115084 0.993356 0.000000
    outer loop
      vertex -84.934654 81.375298 15.000000
      vertex 25.003807 94.112053 15.000000
      vertex 25.003807 94.112053 0.000000
    endloop
  endfacet
  facet normal -0.115084 0.993356 0.000000
    outer loop
      vertex -84.934654 81.375298 15.000000
      vertex 25.003807 94.112053 0.000000
      vertex -84.934654 81.375298 0.000000
    endloop
  endfacet
  facet normal 0.695686 -0.718346 0.000000
    outer loop
      vertex 61.308319 79.666428 0.000000
      vertex 61.308319 79.666428 15.000000
      vertex 46.875835 65.689217 15.000000
    endloop
  endfacet
  facet normal 0.695686 -0.718346 0.000000
    outer loop
      vertex 61.308319 79.666428 0.000000
      vertex 46.875835 65.689217 15.000000
      vertex 46.875835 65.689217 0.000000
    endloop
  endfacet
  facet normal 0.937331 -0.348441 0.000000
    outer loop
      vertex 61.763901 80.891975 0.000000
      vertex 61.308319 79.666428 15.000000
      vertex 61.308319 79.666428 0.000000
    endloop
  endfacet
  facet normal 0.937331 -0.348441 0.000000
    outer loop
      vertex 61.763901 80.891975 15.000000
      vertex 61.308319 79.666428 15.000000
      vertex 61.763901 80.891975 0.000000
    endloop
  endfacet
  facet normal 0.968853 -0.247637 0.000000
    outer loop
      vertex 61.763901 80.891975 15.000000
      vertex 61.763901 80.891975 0.000000
      vertex 62.087681 82.158730 0.000000
    endloop
  endfacet
  facet normal 0.968853 -0.247637 0.000000
    outer loop
      vertex 62.087681 82.158730 15.000000
      vertex 61.763901 80.891975 15.000000
      vertex 62.087681 82.158730 0.000000
    endloop
  endfacet
  facet normal 0.989567 -0.144076 0.000000
    outer loop
      vertex 62.087681 82.158730 15.000000
      vertex 62.087681 82.158730 0.000000
      vertex 62.276058 83.452576 0.000000
    endloop
  endfacet
  facet normal 0.989567 -0.144076 0.000000
    outer loop
      vertex 62.276058 83.452576 15.000000
      vertex 62.087681 82.158730 15.000000
      vertex 62.276058 83.452576 0.000000
    endloop
  endfacet
  facet normal 0.999243 -0.038906 0.000000
    outer loop
      vertex 62.276058 83.452576 15.000000
      vertex 62.276058 83.452576 0.000000
      vertex 62.326927 84.759064 0.000000
    endloop
  endfacet
  facet normal 0.999243 -0.038906 0.000000
    outer loop
      vertex 62.326927 84.759064 15.000000
      vertex 62.276058 83.452576 15.000000
      vertex 62.326927 84.759064 0.000000
    endloop
  endfacet
  facet normal 0.997773 0.066699 0.000000
    outer loop
      vertex 62.326927 84.759064 15.000000
      vertex 62.326927 84.759064 0.000000
      vertex 62.239719 86.063637 0.000000
    endloop
  endfacet
  facet normal 0.997773 0.066699 0.000000
    outer loop
      vertex 62.239719 86.063637 15.000000
      vertex 62.326927 84.759064 15.000000
      vertex 62.239719 86.063637 0.000000
    endloop
  endfacet
  facet normal 0.985174 0.171561 0.000000
    outer loop
      vertex 62.239719 86.063637 15.000000
      vertex 62.239719 86.063637 0.000000
      vertex 62.015408 87.351730 0.000000
    endloop
  endfacet
  facet normal 0.985174 0.171561 0.000000
    outer loop
      vertex 62.015408 87.351730 15.000000
      vertex 62.239719 86.063637 15.000000
      vertex 62.015408 87.351730 0.000000
    endloop
  endfacet
  facet normal 0.961586 0.274505 0.000000
    outer loop
      vertex 62.015408 87.351730 15.000000
      vertex 62.015408 87.351730 0.000000
      vertex 61.656498 88.608986 0.000000
    endloop
  endfacet
  facet normal 0.961586 0.274505 0.000000
    outer loop
      vertex 61.656498 88.608986 15.000000
      vertex 62.015408 87.351730 15.000000
      vertex 61.656498 88.608986 0.000000
    endloop
  endfacet
  facet normal 0.927272 0.374389 0.000000
    outer loop
      vertex 61.656498 88.608986 15.000000
      vertex 61.656498 88.608986 0.000000
      vertex 61.166992 89.821373 0.000000
    endloop
  endfacet
  facet normal 0.927272 0.374389 0.000000
    outer loop
      vertex 61.166992 89.821373 15.000000
      vertex 61.656498 88.608986 15.000000
      vertex 61.166992 89.821373 0.000000
    endloop
  endfacet
  facet normal 0.882614 0.470098 0.000000
    outer loop
      vertex 61.166992 89.821373 15.000000
      vertex 61.166992 89.821373 0.000000
      vertex 60.552345 90.975380 0.000000
    endloop
  endfacet
  facet normal 0.882614 0.470098 0.000000
    outer loop
      vertex 60.552345 90.975380 15.000000
      vertex 61.166992 89.821373 15.000000
      vertex 60.552345 90.975380 0.000000
    endloop
  endfacet
  facet normal 0.828112 0.560563 0.000000
    outer loop
      vertex 60.552345 90.975380 15.000000
      vertex 60.552345 90.975380 0.000000
      vertex 59.819420 92.058121 0.000000
    endloop
  endfacet
  facet normal 0.828112 0.560563 0.000000
    outer loop
      vertex 59.819420 92.058121 15.000000
      vertex 60.552345 90.975380 15.000000
      vertex 59.819420 92.058121 0.000000
    endloop
  endfacet
  facet normal 0.764373 0.644775 0.000000
    outer loop
      vertex 59.819420 92.058121 15.000000
      vertex 59.819420 92.058121 0.000000
      vertex 58.976387 93.057526 0.000000
    endloop
  endfacet
  facet normal 0.764373 0.644775 0.000000
    outer loop
      vertex 58.976387 93.057526 15.000000
      vertex 59.819420 92.058121 15.000000
      vertex 58.976387 93.057526 0.000000
    endloop
  endfacet
  facet normal 0.692109 0.721793 0.000000
    outer loop
      vertex 58.976387 93.057526 15.000000
      vertex 58.976387 93.057526 0.000000
      vertex 58.032654 93.962448 0.000000
    endloop
  endfacet
  facet normal 0.692109 0.721793 0.000000
    outer loop
      vertex 58.032654 93.962448 15.000000
      vertex 58.976387 93.057526 15.000000
      vertex 58.032654 93.962448 0.000000
    endloop
  endfacet
  facet normal 0.612122 0.790763 0.000000
    outer loop
      vertex 58.032654 93.962448 15.000000
      vertex 58.032654 93.962448 0.000000
      vertex 56.998745 94.762787 0.000000
    endloop
  endfacet
  facet normal 0.612122 0.790763 0.000000
    outer loop
      vertex 56.998745 94.762787 15.000000
      vertex 58.032654 93.962448 15.000000
      vertex 56.998745 94.762787 0.000000
    endloop
  endfacet
  facet normal 0.525307 0.850913 0.000000
    outer loop
      vertex 56.998745 94.762787 15.000000
      vertex 56.998745 94.762787 0.000000
      vertex 55.886192 95.449615 0.000000
    endloop
  endfacet
  facet normal 0.525307 0.850913 0.000000
    outer loop
      vertex 55.886192 95.449615 15.000000
      vertex 56.998745 94.762787 15.000000
      vertex 55.886192 95.449615 0.000000
    endloop
  endfacet
  facet normal 0.432638 0.901568 0.000000
    outer loop
      vertex 55.886192 95.449615 15.000000
      vertex 55.886192 95.449615 0.000000
      vertex 54.707409 96.015282 0.000000
    endloop
  endfacet
  facet normal 0.432638 0.901568 0.000000
    outer loop
      vertex 54.707409 96.015282 15.000000
      vertex 55.886192 95.449615 15.000000
      vertex 54.707409 96.015282 0.000000
    endloop
  endfacet
  facet normal 0.335137 0.942169 0.000000
    outer loop
      vertex 54.707409 96.015282 15.000000
      vertex 54.707409 96.015282 0.000000
      vertex 53.475536 96.453468 0.000000
    endloop
  endfacet
  facet normal 0.335137 0.942169 0.000000
    outer loop
      vertex 53.475536 96.453468 15.000000
      vertex 54.707409 96.015282 15.000000
      vertex 53.475536 96.453468 0.000000
    endloop
  endfacet
  facet normal 0.233904 0.972260 0.000000
    outer loop
      vertex 53.475536 96.453468 15.000000
      vertex 53.475536 96.453468 0.000000
      vertex 52.204327 96.759293 0.000000
    endloop
  endfacet
  facet normal 0.233904 0.972260 0.000000
    outer loop
      vertex 52.204327 96.759293 15.000000
      vertex 53.475536 96.453468 15.000000
      vertex 52.204327 96.759293 0.000000
    endloop
  endfacet
  facet normal 0.130054 0.991507 0.000000
    outer loop
      vertex 52.204327 96.759293 15.000000
      vertex 52.204327 96.759293 0.000000
      vertex 50.907948 96.929337 0.000000
    endloop
  endfacet
  facet normal 0.130054 0.991507 0.000000
    outer loop
      vertex 50.907948 96.929337 15.000000
      vertex 52.204327 96.759293 15.000000
      vertex 50.907948 96.929337 0.000000
    endloop
  endfacet
  facet normal 0.024759 0.999693 0.000000
    outer loop
      vertex 50.907948 96.929337 15.000000
      vertex 50.907948 96.929337 0.000000
      vertex 49.600864 96.961708 0.000000
    endloop
  endfacet
  facet normal 0.024759 0.999693 0.000000
    outer loop
      vertex 49.600864 96.961708 15.000000
      vertex 50.907948 96.929337 15.000000
      vertex 49.600864 96.961708 0.000000
    endloop
  endfacet
  facet normal 0.804863 0.593461 0.000000
    outer loop
      vertex -80.165909 5.299218 15.000000
      vertex -77.267235 1.367985 15.000000
      vertex -77.267235 1.367985 0.000000
    endloop
  endfacet
  facet normal 0.804863 0.593461 0.000000
    outer loop
      vertex -80.165909 5.299218 15.000000
      vertex -77.267235 1.367985 0.000000
      vertex -80.165909 5.299218 0.000000
    endloop
  endfacet
  facet normal 0.864442 0.502732 0.000000
    outer loop
      vertex -82.621429 9.521455 15.000000
      vertex -80.165909 5.299218 15.000000
      vertex -80.165909 5.299218 0.000000
    endloop
  endfacet
  facet normal 0.864442 0.502732 0.000000
    outer loop
      vertex -82.621429 9.521455 15.000000
      vertex -80.165909 5.299218 0.000000
      vertex -82.621429 9.521455 0.000000
    endloop
  endfacet
  facet normal 0.913836 0.406084 0.000000
    outer loop
      vertex -84.604889 13.984954 15.000000
      vertex -82.621429 9.521455 15.000000
      vertex -82.621429 9.521455 0.000000
    endloop
  endfacet
  facet normal 0.913836 0.406084 0.000000
    outer loop
      vertex -84.604889 13.984954 15.000000
      vertex -82.621429 9.521455 0.000000
      vertex -84.604889 13.984954 0.000000
    endloop
  endfacet
  facet normal 0.952465 0.304648 0.000000
    outer loop
      vertex -86.092896 18.637129 15.000000
      vertex -84.604889 13.984954 15.000000
      vertex -84.604889 13.984954 0.000000
    endloop
  endfacet
  facet normal 0.952465 0.304648 0.000000
    outer loop
      vertex -86.092896 18.637129 15.000000
      vertex -84.604889 13.984954 0.000000
      vertex -86.092896 18.637129 0.000000
    endloop
  endfacet
  facet normal 0.979873 0.199625 0.000000
    outer loop
      vertex -87.067932 23.423172 15.000000
      vertex -86.092896 18.637129 15.000000
      vertex -86.092896 18.637129 0.000000
    endloop
  endfacet
  facet normal 0.979873 0.199625 0.000000
    outer loop
      vertex -87.067932 23.423172 15.000000
      vertex -86.092896 18.637129 0.000000
      vertex -87.067932 23.423172 0.000000
    endloop
  endfacet
  facet normal 0.995736 0.092249 0.000000
    outer loop
      vertex -87.518509 28.286697 15.000000
      vertex -87.067932 23.423172 15.000000
      vertex -87.067932 23.423172 0.000000
    endloop
  endfacet
  facet normal 0.995736 0.092249 0.000000
    outer loop
      vertex -87.518509 28.286697 15.000000
      vertex -87.067932 23.423172 0.000000
      vertex -87.518509 28.286697 0.000000
    endloop
  endfacet
  facet normal 0.999819 0.019027 0.000000
    outer loop
      vertex -87.551132 30.000978 15.000000
      vertex -87.518509 28.286697 15.000000
      vertex -87.518509 28.286697 0.000000
    endloop
  endfacet
  facet normal 0.999819 0.019027 0.000000
    outer loop
      vertex -87.551132 30.000978 15.000000
      vertex -87.518509 28.286697 0.000000
      vertex -87.551132 30.000978 0.000000
    endloop
  endfacet
  facet normal 0.999378 -0.035258 0.000000
    outer loop
      vertex -87.439316 33.170410 15.000000
      vertex -87.551132 30.000978 15.000000
      vertex -87.551132 30.000978 0.000000
    endloop
  endfacet
  facet normal 0.999378 -0.035258 0.000000
    outer loop
      vertex -87.439316 33.170410 15.000000
      vertex -87.551132 30.000978 0.000000
      vertex -87.439316 33.170410 0.000000
    endloop
  endfacet
  facet normal 0.992221 -0.124487 0.000000
    outer loop
      vertex -86.831276 38.016766 15.000000
      vertex -87.439316 33.170410 15.000000
      vertex -87.439316 33.170410 0.000000
    endloop
  endfacet
  facet normal 0.992221 -0.124487 0.000000
    outer loop
      vertex -86.831276 38.016766 15.000000
      vertex -87.439316 33.170410 0.000000
      vertex -86.831276 38.016766 0.000000
    endloop
  endfacet
  facet normal 0.972885 -0.231289 0.000000
    outer loop
      vertex -85.701576 42.768681 15.000000
      vertex -86.831276 38.016766 15.000000
      vertex -86.831276 38.016766 0.000000
    endloop
  endfacet
  facet normal 0.972885 -0.231289 0.000000
    outer loop
      vertex -85.701576 42.768681 15.000000
      vertex -86.831276 38.016766 0.000000
      vertex -85.701576 42.768681 0.000000
    endloop
  endfacet
  facet normal 0.942086 -0.335371 0.000000
    outer loop
      vertex -84.063507 47.370163 15.000000
      vertex -85.701576 42.768681 15.000000
      vertex -85.701576 42.768681 0.000000
    endloop
  endfacet
  facet normal 0.942086 -0.335371 0.000000
    outer loop
      vertex -84.063507 47.370163 15.000000
      vertex -85.701576 42.768681 0.000000
      vertex -84.063507 47.370163 0.000000
    endloop
  endfacet
  facet normal 0.900189 -0.435500 0.000000
    outer loop
      vertex -81.936371 51.767002 15.000000
      vertex -84.063507 47.370163 15.000000
      vertex -84.063507 47.370163 0.000000
    endloop
  endfacet
  facet normal 0.900189 -0.435500 0.000000
    outer loop
      vertex -81.936371 51.767002 15.000000
      vertex -84.063507 47.370163 0.000000
      vertex -81.936371 51.767002 0.000000
    endloop
  endfacet
  facet normal 0.847687 -0.530497 0.000000
    outer loop
      vertex -79.345238 55.907406 15.000000
      vertex -81.936371 51.767002 15.000000
      vertex -81.936371 51.767002 0.000000
    endloop
  endfacet
  facet normal 0.847687 -0.530497 0.000000
    outer loop
      vertex -79.345238 55.907406 15.000000
      vertex -81.936371 51.767002 0.000000
      vertex -79.345238 55.907406 0.000000
    endloop
  endfacet
  facet normal 0.785197 -0.619246 0.000000
    outer loop
      vertex -76.320625 59.742584 15.000000
      vertex -79.345238 55.907406 15.000000
      vertex -79.345238 55.907406 0.000000
    endloop
  endfacet
  facet normal 0.785197 -0.619246 0.000000
    outer loop
      vertex -76.320625 59.742584 15.000000
      vertex -79.345238 55.907406 0.000000
      vertex -76.320625 59.742584 0.000000
    endloop
  endfacet
  facet normal 0.713457 -0.700699 0.000000
    outer loop
      vertex -72.898163 63.227364 15.000000
      vertex -76.320625 59.742584 15.000000
      vertex -76.320625 59.742584 0.000000
    endloop
  endfacet
  facet normal 0.713457 -0.700699 0.000000
    outer loop
      vertex -72.898163 63.227364 15.000000
      vertex -76.320625 59.742584 0.000000
      vertex -72.898163 63.227364 0.000000
    endloop
  endfacet
  facet normal 0.633312 -0.773897 0.000000
    outer loop
      vertex -69.118179 66.320679 15.000000
      vertex -72.898163 63.227364 15.000000
      vertex -72.898163 63.227364 0.000000
    endloop
  endfacet
  facet normal 0.633312 -0.773897 0.000000
    outer loop
      vertex -69.118179 66.320679 15.000000
      vertex -72.898163 63.227364 0.000000
      vertex -69.118179 66.320679 0.000000
    endloop
  endfacet
  facet normal 0.545706 -0.837977 0.000000
    outer loop
      vertex -65.025208 68.986099 15.000000
      vertex -69.118179 66.320679 15.000000
      vertex -69.118179 66.320679 0.000000
    endloop
  endfacet
  facet normal 0.545706 -0.837977 0.000000
    outer loop
      vertex -65.025208 68.986099 15.000000
      vertex -69.118179 66.320679 0.000000
      vertex -65.025208 68.986099 0.000000
    endloop
  endfacet
  facet normal 0.451670 -0.892185 0.000000
    outer loop
      vertex -60.667461 71.192215 15.000000
      vertex -65.025208 68.986099 15.000000
      vertex -65.025208 68.986099 0.000000
    endloop
  endfacet
  facet normal 0.451670 -0.892185 0.000000
    outer loop
      vertex -60.667461 71.192215 15.000000
      vertex -65.025208 68.986099 0.000000
      vertex -60.667461 71.192215 0.000000
    endloop
  endfacet
  facet normal 0.352312 -0.935882 0.000000
    outer loop
      vertex -56.096283 72.913033 15.000000
      vertex -60.667461 71.192215 15.000000
      vertex -60.667461 71.192215 0.000000
    endloop
  endfacet
  facet normal 0.352312 -0.935882 0.000000
    outer loop
      vertex -56.096283 72.913033 15.000000
      vertex -60.667461 71.192215 0.000000
      vertex -56.096283 72.913033 0.000000
    endloop
  endfacet
  facet normal 0.248807 -0.968553 0.000000
    outer loop
      vertex -51.365528 74.128296 15.000000
      vertex -56.096283 72.913033 15.000000
      vertex -56.096283 72.913033 0.000000
    endloop
  endfacet
  facet normal 0.248807 -0.968553 0.000000
    outer loop
      vertex -51.365528 74.128296 15.000000
      vertex -56.096283 72.913033 0.000000
      vertex -51.365528 74.128296 0.000000
    endloop
  endfacet
  facet normal 0.142368 -0.989814 0.000000
    outer loop
      vertex -46.530926 74.823669 15.000000
      vertex -51.365528 74.128296 15.000000
      vertex -51.365528 74.128296 0.000000
    endloop
  endfacet
  facet normal 0.142368 -0.989814 0.000000
    outer loop
      vertex -46.530926 74.823669 15.000000
      vertex -51.365528 74.128296 0.000000
      vertex -46.530926 74.823669 0.000000
    endloop
  endfacet
  facet normal 0.034252 -0.999413 0.000000
    outer loop
      vertex -41.649437 74.990967 15.000000
      vertex -46.530926 74.823669 15.000000
      vertex -46.530926 74.823669 0.000000
    endloop
  endfacet
  facet normal 0.034252 -0.999413 0.000000
    outer loop
      vertex -41.649437 74.990967 15.000000
      vertex -46.530926 74.823669 0.000000
      vertex -41.649437 74.990967 0.000000
    endloop
  endfacet
  facet normal -0.074269 -0.997238 0.000000
    outer loop
      vertex -36.778576 74.628212 15.000000
      vertex -41.649437 74.990967 15.000000
      vertex -41.649437 74.990967 0.000000
    endloop
  endfacet
  facet normal -0.074269 -0.997238 -0.000000
    outer loop
      vertex -36.778576 74.628212 15.000000
      vertex -41.649437 74.990967 0.000000
      vertex -36.778576 74.628212 0.000000
    endloop
  endfacet
  facet normal -0.181911 -0.983315 0.000000
    outer loop
      vertex -31.975719 73.739693 15.000000
      vertex -36.778576 74.628212 15.000000
      vertex -36.778576 74.628212 0.000000
    endloop
  endfacet
  facet normal -0.181911 -0.983315 -0.000000
    outer loop
      vertex -31.975719 73.739693 15.000000
      vertex -36.778576 74.628212 0.000000
      vertex -31.975719 73.739693 0.000000
    endloop
  endfacet
  facet normal -0.287414 -0.957806 0.000000
    outer loop
      vertex -27.297455 72.335861 15.000000
      vertex -31.975719 73.739693 15.000000
      vertex -31.975719 73.739693 0.000000
    endloop
  endfacet
  facet normal -0.287414 -0.957806 -0.000000
    outer loop
      vertex -27.297455 72.335861 15.000000
      vertex -31.975719 73.739693 0.000000
      vertex -27.297455 72.335861 0.000000
    endloop
  endfacet
  facet normal -0.389529 -0.921014 0.000000
    outer loop
      vertex -22.798897 70.433266 15.000000
      vertex -27.297455 72.335861 15.000000
      vertex -27.297455 72.335861 0.000000
    endloop
  endfacet
  facet normal -0.389529 -0.921014 -0.000000
    outer loop
      vertex -22.798897 70.433266 15.000000
      vertex -27.297455 72.335861 0.000000
      vertex -22.798897 70.433266 0.000000
    endloop
  endfacet
  facet normal -0.487054 -0.873372 0.000000
    outer loop
      vertex -18.533041 68.054321 15.000000
      vertex -22.798897 70.433266 15.000000
      vertex -22.798897 70.433266 0.000000
    endloop
  endfacet
  facet normal -0.487054 -0.873372 -0.000000
    outer loop
      vertex -18.533041 68.054321 15.000000
      vertex -22.798897 70.433266 0.000000
      vertex -18.533041 68.054321 0.000000
    endloop
  endfacet
  facet normal -0.578844 -0.815439 0.000000
    outer loop
      vertex -14.550149 65.227043 15.000000
      vertex -18.533041 68.054321 15.000000
      vertex -18.533041 68.054321 0.000000
    endloop
  endfacet
  facet normal -0.578844 -0.815439 -0.000000
    outer loop
      vertex -14.550149 65.227043 15.000000
      vertex -18.533041 68.054321 0.000000
      vertex -14.550149 65.227043 0.000000
    endloop
  endfacet
  facet normal -0.663811 -0.747901 0.000000
    outer loop
      vertex -10.897141 61.984760 15.000000
      vertex -14.550149 65.227043 15.000000
      vertex -14.550149 65.227043 0.000000
    endloop
  endfacet
  facet normal -0.663811 -0.747901 -0.000000
    outer loop
      vertex -10.897141 61.984760 15.000000
      vertex -14.550149 65.227043 0.000000
      vertex -10.897141 61.984760 0.000000
    endloop
  endfacet
  facet normal -0.740960 -0.671549 0.000000
    outer loop
      vertex -7.617054 58.365650 15.000000
      vertex -10.897141 61.984760 15.000000
      vertex -10.897141 61.984760 0.000000
    endloop
  endfacet
  facet normal -0.740960 -0.671549 -0.000000
    outer loop
      vertex -7.617054 58.365650 15.000000
      vertex -10.897141 61.984760 0.000000
      vertex -7.617054 58.365650 0.000000
    endloop
  endfacet
  facet normal -0.809378 -0.587288 0.000000
    outer loop
      vertex -4.748533 54.412365 15.000000
      vertex -7.617054 58.365650 15.000000
      vertex -7.617054 58.365650 0.000000
    endloop
  endfacet
  facet normal -0.809378 -0.587288 -0.000000
    outer loop
      vertex -4.748533 54.412365 15.000000
      vertex -7.617054 58.365650 0.000000
      vertex -4.748533 54.412365 0.000000
    endloop
  endfacet
  facet normal -0.868262 -0.496107 0.000000
    outer loop
      vertex -2.325371 50.171467 15.000000
      vertex -4.748533 54.412365 15.000000
      vertex -4.748533 54.412365 0.000000
    endloop
  endfacet
  facet normal -0.868262 -0.496107 -0.000000
    outer loop
      vertex -2.325371 50.171467 15.000000
      vertex -4.748533 54.412365 0.000000
      vertex -2.325371 50.171467 0.000000
    endloop
  endfacet
  facet normal -0.916915 -0.399082 0.000000
    outer loop
      vertex -0.376117 45.692932 15.000000
      vertex -2.325371 50.171467 15.000000
      vertex -2.325371 50.171467 0.000000
    endloop
  endfacet
  facet normal -0.916915 -0.399082 -0.000000
    outer loop
      vertex -0.376117 45.692932 15.000000
      vertex -2.325371 50.171467 0.000000
      vertex -0.376117 45.692932 0.000000
    endloop
  endfacet
  facet normal -0.954767 -0.297354 0.000000
    outer loop
      vertex 1.076266 41.029510 15.000000
      vertex -0.376117 45.692932 15.000000
      vertex -0.376117 45.692932 0.000000
    endloop
  endfacet
  facet normal -0.954767 -0.297354 -0.000000
    outer loop
      vertex 1.076266 41.029510 15.000000
      vertex -0.376117 45.692932 0.000000
      vertex 1.076266 41.029510 0.000000
    endloop
  endfacet
  facet normal -0.981371 -0.192124 0.000000
    outer loop
      vertex 2.014667 36.236149 15.000000
      vertex 1.076266 41.029510 15.000000
      vertex 1.076266 41.029510 0.000000
    endloop
  endfacet
  facet normal -0.981371 -0.192124 -0.000000
    outer loop
      vertex 2.014667 36.236149 15.000000
      vertex 1.076266 41.029510 0.000000
      vertex 2.014667 36.236149 0.000000
    endloop
  endfacet
  facet normal -0.996412 -0.084630 0.000000
    outer loop
      vertex 2.428029 31.369322 15.000000
      vertex 2.014667 36.236149 15.000000
      vertex 2.014667 36.236149 0.000000
    endloop
  endfacet
  facet normal -0.996412 -0.084630 -0.000000
    outer loop
      vertex 2.428029 31.369322 15.000000
      vertex 2.014667 36.236149 0.000000
      vertex 2.428029 31.369322 0.000000
    endloop
  endfacet
  facet normal -0.999884 -0.015202 0.000000
    outer loop
      vertex 2.448868 29.998724 15.000000
      vertex 2.428029 31.369322 15.000000
      vertex 2.428029 31.369322 0.000000
    endloop
  endfacet
  facet normal -0.999884 -0.015202 -0.000000
    outer loop
      vertex 2.448868 29.998724 15.000000
      vertex 2.428029 31.369322 0.000000
      vertex 2.448868 29.998724 0.000000
    endloop
  endfacet
  facet normal -0.999236 0.039085 0.000000
    outer loop
      vertex 2.311483 26.486357 15.000000
      vertex 2.448868 29.998724 15.000000
      vertex 2.448868 29.998724 0.000000
    endloop
  endfacet
  facet normal -0.999236 0.039085 0.000000
    outer loop
      vertex 2.311483 26.486357 15.000000
      vertex 2.448868 29.998724 0.000000
      vertex 2.311483 26.486357 0.000000
    endloop
  endfacet
  facet normal -0.991240 0.132071 0.000000
    outer loop
      vertex 1.666403 21.644791 15.000000
      vertex 2.311483 26.486357 15.000000
      vertex 2.311483 26.486357 0.000000
    endloop
  endfacet
  facet normal -0.991240 0.132071 0.000000
    outer loop
      vertex 1.666403 21.644791 15.000000
      vertex 2.311483 26.486357 0.000000
      vertex 1.666403 21.644791 0.000000
    endloop
  endfacet
  facet normal -0.971087 0.238725 0.000000
    outer loop
      vertex 0.500388 16.901657 15.000000
      vertex 1.666403 21.644791 15.000000
      vertex 1.666403 21.644791 0.000000
    endloop
  endfacet
  facet normal -0.971087 0.238725 0.000000
    outer loop
      vertex 0.500388 16.901657 15.000000
      vertex 1.666403 21.644791 0.000000
      vertex 0.500388 16.901657 0.000000
    endloop
  endfacet
  facet normal -0.939494 0.342566 0.000000
    outer loop
      vertex -1.172825 12.312838 15.000000
      vertex 0.500388 16.901657 15.000000
      vertex 0.500388 16.901657 0.000000
    endloop
  endfacet
  facet normal -0.939494 0.342566 0.000000
    outer loop
      vertex -1.172825 12.312838 15.000000
      vertex 0.500388 16.901657 0.000000
      vertex -1.172825 12.312838 0.000000
    endloop
  endfacet
  facet normal -0.896832 0.442372 0.000000
    outer loop
      vertex -3.333524 7.932395 15.000000
      vertex -1.172825 12.312838 15.000000
      vertex -1.172825 12.312838 0.000000
    endloop
  endfacet
  facet normal -0.896832 0.442372 0.000000
    outer loop
      vertex -3.333524 7.932395 15.000000
      vertex -1.172825 12.312838 0.000000
      vertex -3.333524 7.932395 0.000000
    endloop
  endfacet
  facet normal -0.843604 0.536966 0.000000
    outer loop
      vertex -5.956253 3.811934 15.000000
      vertex -3.333524 7.932395 15.000000
      vertex -3.333524 7.932395 0.000000
    endloop
  endfacet
  facet normal -0.843604 0.536966 0.000000
    outer loop
      vertex -5.956253 3.811934 15.000000
      vertex -3.333524 7.932395 0.000000
      vertex -5.956253 3.811934 0.000000
    endloop
  endfacet
  facet normal -0.780438 0.625233 0.000000
    outer loop
      vertex -9.010113 0.000000 15.000000
      vertex -5.956253 3.811934 15.000000
      vertex -5.956253 3.811934 0.000000
    endloop
  endfacet
  facet normal -0.780438 0.625233 0.000000
    outer loop
      vertex -9.010113 0.000000 15.000000
      vertex -5.956253 3.811934 0.000000
      vertex -9.010113 0.000000 0.000000
    endloop
  endfacet
  facet normal -0.489708 -0.871886 0.000000
    outer loop
      vertex 1.434067 -12.024600 0.000000
      vertex 2.877826 -12.835510 0.000000
      vertex 2.877826 -12.835510 15.000000
    endloop
  endfacet
  facet normal -0.504638 -0.863329 0.001900
    outer loop
      vertex 1.434067 -12.024600 0.000000
      vertex 2.877826 -12.835510 15.000000
      vertex 0.677891 -11.549590 15.000000
    endloop
  endfacet
  facet normal -0.531930 -0.846788 0.000000
    outer loop
      vertex 0.677891 -11.549590 0.000000
      vertex 1.434067 -12.024600 0.000000
      vertex 0.677891 -11.549590 15.000000
    endloop
  endfacet
  facet normal -0.586889 -0.809667 0.000000
    outer loop
      vertex 0.677891 -11.549590 0.000000
      vertex 0.677891 -11.549590 15.000000
      vertex -1.385300 -10.054082 15.000000
    endloop
  endfacet
  facet normal -0.586889 -0.809667 0.000000
    outer loop
      vertex -1.385300 -10.054082 0.000000
      vertex 0.677891 -11.549590 0.000000
      vertex -1.385300 -10.054082 15.000000
    endloop
  endfacet
  facet normal -0.663479 -0.748195 0.000000
    outer loop
      vertex -1.385300 -10.054082 0.000000
      vertex -1.385300 -10.054082 15.000000
      vertex -3.291848 -8.363408 15.000000
    endloop
  endfacet
  facet normal -0.663479 -0.748195 0.000000
    outer loop
      vertex -3.291848 -8.363408 0.000000
      vertex -1.385300 -10.054082 0.000000
      vertex -3.291848 -8.363408 15.000000
    endloop
  endfacet
  facet normal -0.733669 -0.679507 0.000000
    outer loop
      vertex -3.291848 -8.363408 0.000000
      vertex -3.291848 -8.363408 15.000000
      vertex -5.023365 -6.493875 15.000000
    endloop
  endfacet
  facet normal -0.733669 -0.679507 0.000000
    outer loop
      vertex -5.023365 -6.493875 0.000000
      vertex -3.291848 -8.363408 0.000000
      vertex -5.023365 -6.493875 15.000000
    endloop
  endfacet
  facet normal -0.796784 -0.604265 0.000000
    outer loop
      vertex -5.023365 -6.493875 0.000000
      vertex -5.023365 -6.493875 15.000000
      vertex -6.563149 -4.463514 15.000000
    endloop
  endfacet
  facet normal -0.796784 -0.604265 0.000000
    outer loop
      vertex -6.563149 -4.463514 0.000000
      vertex -5.023365 -6.493875 0.000000
      vertex -6.563149 -4.463514 15.000000
    endloop
  endfacet
  facet normal -0.852213 -0.523195 0.000000
    outer loop
      vertex -6.563149 -4.463514 0.000000
      vertex -6.563149 -4.463514 15.000000
      vertex -7.896352 -2.291907 15.000000
    endloop
  endfacet
  facet normal -0.852213 -0.523195 0.000000
    outer loop
      vertex -7.896352 -2.291907 0.000000
      vertex -6.563149 -4.463514 0.000000
      vertex -7.896352 -2.291907 15.000000
    endloop
  endfacet
  facet normal -0.899423 -0.437078 0.000000
    outer loop
      vertex -7.896352 -2.291907 0.000000
      vertex -7.896352 -2.291907 15.000000
      vertex -9.010113 0.000000 15.000000
    endloop
  endfacet
  facet normal -0.899423 -0.437078 0.000000
    outer loop
      vertex -9.010113 0.000000 0.000000
      vertex -7.896352 -2.291907 0.000000
      vertex -9.010113 0.000000 15.000000
    endloop
  endfacet
  facet normal -0.461637 -0.887069 -0.000000
    outer loop
      vertex 47.169426 -35.885197 15.000000
      vertex 41.827843 -33.105396 0.000000
      vertex 47.169426 -35.885197 0.000000
    endloop
  endfacet
  facet normal -0.461637 -0.887069 0.000000
    outer loop
      vertex 25.003807 -24.350040 15.000000
      vertex 2.877826 -12.835510 15.000000
      vertex 2.877826 -12.835510 0.000000
    endloop
  endfacet
  facet normal -0.461637 -0.887069 -0.000000
    outer loop
      vertex 25.003807 -24.350040 15.000000
      vertex 2.877826 -12.835510 0.000000
      vertex 41.827843 -33.105396 0.000000
    endloop
  endfacet
  facet normal -0.461637 -0.887069 -0.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 25.003807 -24.350040 15.000000
      vertex 41.827843 -33.105396 0.000000
    endloop
  endfacet
  facet normal -0.461637 -0.887069 -0.000000
    outer loop
      vertex 41.827843 -33.105396 15.000000
      vertex 41.827843 -33.105396 0.000000
      vertex 47.169426 -35.885197 15.000000
    endloop
  endfacet
  facet normal -0.176703 -0.984264 0.000000
    outer loop
      vertex 48.468369 -36.118393 0.000000
      vertex 47.169426 -35.885197 15.000000
      vertex 47.169426 -35.885197 0.000000
    endloop
  endfacet
  facet normal -0.176703 -0.984264 -0.000000
    outer loop
      vertex 48.468369 -36.118393 15.000000
      vertex 47.169426 -35.885197 15.000000
      vertex 48.468369 -36.118393 0.000000
    endloop
  endfacet
  facet normal -0.069006 -0.997616 -0.000000
    outer loop
      vertex 48.468369 -36.118393 15.000000
      vertex 48.468369 -36.118393 0.000000
      vertex 49.784931 -36.209461 0.000000
    endloop
  endfacet
  facet normal -0.069006 -0.997616 -0.000000
    outer loop
      vertex 49.784931 -36.209461 15.000000
      vertex 48.468369 -36.118393 15.000000
      vertex 49.784931 -36.209461 0.000000
    endloop
  endfacet
  facet normal 0.039499 -0.999220 0.000000
    outer loop
      vertex 49.784931 -36.209461 15.000000
      vertex 49.784931 -36.209461 0.000000
      vertex 51.103615 -36.157333 0.000000
    endloop
  endfacet
  facet normal 0.039499 -0.999220 0.000000
    outer loop
      vertex 51.103615 -36.157333 15.000000
      vertex 49.784931 -36.209461 15.000000
      vertex 51.103615 -36.157333 0.000000
    endloop
  endfacet
  facet normal 0.147540 -0.989056 0.000000
    outer loop
      vertex 51.103615 -36.157333 15.000000
      vertex 51.103615 -36.157333 0.000000
      vertex 52.408882 -35.962624 0.000000
    endloop
  endfacet
  facet normal 0.147540 -0.989056 0.000000
    outer loop
      vertex 52.408882 -35.962624 15.000000
      vertex 51.103615 -36.157333 15.000000
      vertex 52.408882 -35.962624 0.000000
    endloop
  endfacet
  facet normal 0.253849 -0.967244 0.000000
    outer loop
      vertex 52.408882 -35.962624 15.000000
      vertex 52.408882 -35.962624 0.000000
      vertex 53.685364 -35.627617 0.000000
    endloop
  endfacet
  facet normal 0.253849 -0.967244 0.000000
    outer loop
      vertex 53.685364 -35.627617 15.000000
      vertex 52.408882 -35.962624 15.000000
      vertex 53.685364 -35.627617 0.000000
    endloop
  endfacet
  facet normal 0.357160 -0.934043 0.000000
    outer loop
      vertex 53.685364 -35.627617 15.000000
      vertex 53.685364 -35.627617 0.000000
      vertex 54.918030 -35.156269 0.000000
    endloop
  endfacet
  facet normal 0.357160 -0.934043 0.000000
    outer loop
      vertex 54.918030 -35.156269 15.000000
      vertex 53.685364 -35.627617 15.000000
      vertex 54.918030 -35.156269 0.000000
    endloop
  endfacet
  facet normal 0.456273 -0.889840 0.000000
    outer loop
      vertex 54.918030 -35.156269 15.000000
      vertex 54.918030 -35.156269 0.000000
      vertex 56.092358 -34.554123 0.000000
    endloop
  endfacet
  facet normal 0.456273 -0.889840 0.000000
    outer loop
      vertex 56.092358 -34.554123 15.000000
      vertex 54.918030 -35.156269 15.000000
      vertex 56.092358 -34.554123 0.000000
    endloop
  endfacet
  facet normal 0.550005 -0.835161 0.000000
    outer loop
      vertex 56.092358 -34.554123 15.000000
      vertex 56.092358 -34.554123 0.000000
      vertex 57.194530 -33.828274 0.000000
    endloop
  endfacet
  facet normal 0.550005 -0.835161 0.000000
    outer loop
      vertex 57.194530 -33.828274 15.000000
      vertex 56.092358 -34.554123 15.000000
      vertex 57.194530 -33.828274 0.000000
    endloop
  endfacet
  facet normal 0.637264 -0.770646 0.000000
    outer loop
      vertex 57.194530 -33.828274 15.000000
      vertex 57.194530 -33.828274 0.000000
      vertex 58.211559 -32.987270 0.000000
    endloop
  endfacet
  facet normal 0.637264 -0.770646 0.000000
    outer loop
      vertex 58.211559 -32.987270 15.000000
      vertex 57.194530 -33.828274 15.000000
      vertex 58.211559 -32.987270 0.000000
    endloop
  endfacet
  facet normal 0.717020 -0.697052 0.000000
    outer loop
      vertex 58.211559 -32.987270 15.000000
      vertex 58.211559 -32.987270 0.000000
      vertex 59.131466 -32.041012 0.000000
    endloop
  endfacet
  facet normal 0.717020 -0.697052 0.000000
    outer loop
      vertex 59.131466 -32.041012 15.000000
      vertex 58.211559 -32.987270 15.000000
      vertex 59.131466 -32.041012 0.000000
    endloop
  endfacet
  facet normal 0.788328 -0.615255 0.000000
    outer loop
      vertex 59.131466 -32.041012 15.000000
      vertex 59.131466 -32.041012 0.000000
      vertex 59.943424 -31.000648 0.000000
    endloop
  endfacet
  facet normal 0.788328 -0.615255 0.000000
    outer loop
      vertex 59.943424 -31.000648 15.000000
      vertex 59.131466 -32.041012 15.000000
      vertex 59.943424 -31.000648 0.000000
    endloop
  endfacet
  facet normal 0.850356 -0.526208 0.000000
    outer loop
      vertex 59.943424 -31.000648 15.000000
      vertex 59.943424 -31.000648 0.000000
      vertex 60.637867 -29.878424 0.000000
    endloop
  endfacet
  facet normal 0.850356 -0.526208 0.000000
    outer loop
      vertex 60.637867 -29.878424 15.000000
      vertex 59.943424 -31.000648 15.000000
      vertex 60.637867 -29.878424 0.000000
    endloop
  endfacet
  facet normal 0.902369 -0.430965 0.000000
    outer loop
      vertex 60.637867 -29.878424 15.000000
      vertex 60.637867 -29.878424 0.000000
      vertex 61.206615 -28.687559 0.000000
    endloop
  endfacet
  facet normal 0.902369 -0.430965 0.000000
    outer loop
      vertex 61.206615 -28.687559 15.000000
      vertex 60.637867 -29.878424 15.000000
      vertex 61.206615 -28.687559 0.000000
    endloop
  endfacet
  facet normal 0.943753 -0.330651 0.000000
    outer loop
      vertex 61.206615 -28.687559 15.000000
      vertex 61.206615 -28.687559 0.000000
      vertex 61.642979 -27.442078 0.000000
    endloop
  endfacet
  facet normal 0.943753 -0.330651 0.000000
    outer loop
      vertex 61.642979 -27.442078 15.000000
      vertex 61.206615 -28.687559 15.000000
      vertex 61.642979 -27.442078 0.000000
    endloop
  endfacet
  facet normal 0.974026 -0.226437 0.000000
    outer loop
      vertex 61.642979 -27.442078 15.000000
      vertex 61.642979 -27.442078 0.000000
      vertex 61.941811 -26.156645 0.000000
    endloop
  endfacet
  facet normal 0.974026 -0.226437 0.000000
    outer loop
      vertex 61.941811 -26.156645 15.000000
      vertex 61.642979 -27.442078 15.000000
      vertex 61.941811 -26.156645 0.000000
    endloop
  endfacet
  facet normal 0.992827 -0.119556 0.000000
    outer loop
      vertex 61.941811 -26.156645 15.000000
      vertex 61.941811 -26.156645 0.000000
      vertex 62.099590 -24.846401 0.000000
    endloop
  endfacet
  facet normal 0.992827 -0.119556 0.000000
    outer loop
      vertex 62.099590 -24.846401 15.000000
      vertex 61.941811 -26.156645 15.000000
      vertex 62.099590 -24.846401 0.000000
    endloop
  endfacet
  facet normal 0.999936 -0.011276 0.000000
    outer loop
      vertex 62.099590 -24.846401 15.000000
      vertex 62.099590 -24.846401 0.000000
      vertex 62.114471 -23.526775 0.000000
    endloop
  endfacet
  facet normal 0.999936 -0.011276 0.000000
    outer loop
      vertex 62.114471 -23.526775 15.000000
      vertex 62.099590 -24.846401 15.000000
      vertex 62.114471 -23.526775 0.000000
    endloop
  endfacet
  facet normal 0.995270 0.097146 0.000000
    outer loop
      vertex 62.114471 -23.526775 15.000000
      vertex 62.114471 -23.526775 0.000000
      vertex 61.986267 -22.213308 0.000000
    endloop
  endfacet
  facet normal 0.995270 0.097146 0.000000
    outer loop
      vertex 61.986267 -22.213308 15.000000
      vertex 62.114471 -23.526775 15.000000
      vertex 61.986267 -22.213308 0.000000
    endloop
  endfacet
  facet normal 0.978883 0.204420 0.000000
    outer loop
      vertex 61.986267 -22.213308 15.000000
      vertex 61.986267 -22.213308 0.000000
      vertex 61.716492 -20.921465 0.000000
    endloop
  endfacet
  facet normal 0.978883 0.204420 0.000000
    outer loop
      vertex 61.716492 -20.921465 15.000000
      vertex 61.986267 -22.213308 15.000000
      vertex 61.716492 -20.921465 0.000000
    endloop
  endfacet
  facet normal 0.950968 0.309289 0.000000
    outer loop
      vertex 61.716492 -20.921465 15.000000
      vertex 61.716492 -20.921465 0.000000
      vertex 61.308319 -19.666462 0.000000
    endloop
  endfacet
  facet normal 0.950968 0.309289 0.000000
    outer loop
      vertex 61.308319 -19.666462 15.000000
      vertex 61.716492 -20.921465 15.000000
      vertex 61.308319 -19.666462 0.000000
    endloop
  endfacet
  facet normal 0.806201 0.591641 -0.000000
    outer loop
      vertex 46.875835 0.000000 0.000000
      vertex 46.875835 0.000000 15.000000
      vertex 61.308319 -19.666462 15.000000
    endloop
  endfacet
  facet normal 0.806201 0.591641 0.000000
    outer loop
      vertex 46.875835 0.000000 0.000000
      vertex 61.308319 -19.666462 15.000000
      vertex 61.308319 -19.666462 0.000000
    endloop
  endfacet
  facet normal 0.998534 -0.054135 0.000000
    outer loop
      vertex 45.588074 85.540596 15.000000
      vertex 45.558765 85.000000 15.000000
      vertex 45.558765 85.000000 0.000000
    endloop
  endfacet
  facet normal 0.998534 -0.054135 0.000000
    outer loop
      vertex 45.588074 85.540596 15.000000
      vertex 45.558765 85.000000 0.000000
      vertex 45.588074 85.540596 0.000000
    endloop
  endfacet
  facet normal 0.986826 -0.161786 0.000000
    outer loop
      vertex 45.675663 86.074852 15.000000
      vertex 45.588074 85.540596 15.000000
      vertex 45.588074 85.540596 0.000000
    endloop
  endfacet
  facet normal 0.986826 -0.161786 0.000000
    outer loop
      vertex 45.675663 86.074852 15.000000
      vertex 45.588074 85.540596 0.000000
      vertex 45.675663 86.074852 0.000000
    endloop
  endfacet
  facet normal 0.963553 -0.267519 0.000000
    outer loop
      vertex 45.820496 86.596512 15.000000
      vertex 45.675663 86.074852 15.000000
      vertex 45.675663 86.074852 0.000000
    endloop
  endfacet
  facet normal 0.963553 -0.267519 0.000000
    outer loop
      vertex 45.820496 86.596512 15.000000
      vertex 45.675663 86.074852 0.000000
      vertex 45.820496 86.596512 0.000000
    endloop
  endfacet
  facet normal 0.928973 -0.370146 0.000000
    outer loop
      vertex 46.020889 87.099449 15.000000
      vertex 45.820496 86.596512 15.000000
      vertex 45.820496 86.596512 0.000000
    endloop
  endfacet
  facet normal 0.928973 -0.370146 0.000000
    outer loop
      vertex 46.020889 87.099449 15.000000
      vertex 45.820496 86.596512 0.000000
      vertex 46.020889 87.099449 0.000000
    endloop
  endfacet
  facet normal 0.883511 -0.468411 0.000000
    outer loop
      vertex 46.274479 87.577766 15.000000
      vertex 46.020889 87.099449 15.000000
      vertex 46.020889 87.099449 0.000000
    endloop
  endfacet
  facet normal 0.883511 -0.468411 0.000000
    outer loop
      vertex 46.274479 87.577766 15.000000
      vertex 46.020889 87.099449 0.000000
      vertex 46.274479 87.577766 0.000000
    endloop
  endfacet
  facet normal 0.827690 -0.561186 0.000000
    outer loop
      vertex 46.578300 88.025871 15.000000
      vertex 46.274479 87.577766 15.000000
      vertex 46.274479 87.577766 0.000000
    endloop
  endfacet
  facet normal 0.827690 -0.561186 0.000000
    outer loop
      vertex 46.578300 88.025871 15.000000
      vertex 46.274479 87.577766 0.000000
      vertex 46.578300 88.025871 0.000000
    endloop
  endfacet
  facet normal 0.762165 -0.647383 0.000000
    outer loop
      vertex 46.928787 88.438499 15.000000
      vertex 46.578300 88.025871 15.000000
      vertex 46.578300 88.025871 0.000000
    endloop
  endfacet
  facet normal 0.762165 -0.647383 0.000000
    outer loop
      vertex 46.928787 88.438499 15.000000
      vertex 46.578300 88.025871 0.000000
      vertex 46.928787 88.438499 0.000000
    endloop
  endfacet
  facet normal 0.687692 -0.726002 0.000000
    outer loop
      vertex 47.321835 88.810806 15.000000
      vertex 46.928787 88.438499 15.000000
      vertex 46.928787 88.438499 0.000000
    endloop
  endfacet
  facet normal 0.687692 -0.726002 0.000000
    outer loop
      vertex 47.321835 88.810806 15.000000
      vertex 46.928787 88.438499 0.000000
      vertex 47.321835 88.810806 0.000000
    endloop
  endfacet
  facet normal 0.605189 -0.796082 0.000000
    outer loop
      vertex 47.752827 89.138451 15.000000
      vertex 47.321835 88.810806 15.000000
      vertex 47.321835 88.810806 0.000000
    endloop
  endfacet
  facet normal 0.605189 -0.796082 0.000000
    outer loop
      vertex 47.752827 89.138451 15.000000
      vertex 47.321835 88.810806 0.000000
      vertex 47.752827 89.138451 0.000000
    endloop
  endfacet
  facet normal 0.515548 -0.856861 0.000000
    outer loop
      vertex 48.216724 89.417564 15.000000
      vertex 47.752827 89.138451 15.000000
      vertex 47.752827 89.138451 0.000000
    endloop
  endfacet
  facet normal 0.515548 -0.856861 0.000000
    outer loop
      vertex 48.216724 89.417564 15.000000
      vertex 47.752827 89.138451 0.000000
      vertex 48.216724 89.417564 0.000000
    endloop
  endfacet
  facet normal 0.419894 -0.907573 0.000000
    outer loop
      vertex 48.708073 89.644890 15.000000
      vertex 48.216724 89.417564 15.000000
      vertex 48.216724 89.417564 0.000000
    endloop
  endfacet
  facet normal 0.419894 -0.907573 0.000000
    outer loop
      vertex 48.708073 89.644890 15.000000
      vertex 48.216724 89.417564 0.000000
      vertex 48.708073 89.644890 0.000000
    endloop
  endfacet
  facet normal 0.319291 -0.947657 0.000000
    outer loop
      vertex 49.221119 89.817749 15.000000
      vertex 48.708073 89.644890 15.000000
      vertex 48.708073 89.644890 0.000000
    endloop
  endfacet
  facet normal 0.319291 -0.947657 0.000000
    outer loop
      vertex 49.221119 89.817749 15.000000
      vertex 48.708073 89.644890 0.000000
      vertex 49.221119 89.817749 0.000000
    endloop
  endfacet
  facet normal 0.214975 -0.976620 0.000000
    outer loop
      vertex 49.749855 89.934135 15.000000
      vertex 49.221119 89.817749 15.000000
      vertex 49.221119 89.817749 0.000000
    endloop
  endfacet
  facet normal 0.214975 -0.976620 0.000000
    outer loop
      vertex 49.749855 89.934135 15.000000
      vertex 49.221119 89.817749 0.000000
      vertex 49.749855 89.934135 0.000000
    endloop
  endfacet
  facet normal 0.108116 -0.994138 0.000000
    outer loop
      vertex 50.288071 89.992668 15.000000
      vertex 49.749855 89.934135 15.000000
      vertex 49.749855 89.934135 0.000000
    endloop
  endfacet
  facet normal 0.108116 -0.994138 0.000000
    outer loop
      vertex 50.288071 89.992668 15.000000
      vertex 49.749855 89.934135 0.000000
      vertex 50.288071 89.992668 0.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex 50.829460 89.992668 15.000000
      vertex 50.288071 89.992668 15.000000
      vertex 50.288071 89.992668 0.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex 50.829460 89.992668 15.000000
      vertex 50.288071 89.992668 0.000000
      vertex 50.829460 89.992668 0.000000
    endloop
  endfacet
  facet normal -0.108116 -0.994138 0.000000
    outer loop
      vertex 51.367676 89.934135 15.000000
      vertex 50.829460 89.992668 15.000000
      vertex 50.829460 89.992668 0.000000
    endloop
  endfacet
  facet normal -0.108116 -0.994138 -0.000000
    outer loop
      vertex 51.367676 89.934135 15.000000
      vertex 50.829460 89.992668 0.000000
      vertex 51.367676 89.934135 0.000000
    endloop
  endfacet
  facet normal -0.214978 -0.976619 0.000000
    outer loop
      vertex 51.896404 89.817749 15.000000
      vertex 51.367676 89.934135 15.000000
      vertex 51.367676 89.934135 0.000000
    endloop
  endfacet
  facet normal -0.214978 -0.976619 -0.000000
    outer loop
      vertex 51.896404 89.817749 15.000000
      vertex 51.367676 89.934135 0.000000
      vertex 51.896404 89.817749 0.000000
    endloop
  endfacet
  facet normal -0.319289 -0.947657 0.000000
    outer loop
      vertex 52.409454 89.644890 15.000000
      vertex 51.896404 89.817749 15.000000
      vertex 51.896404 89.817749 0.000000
    endloop
  endfacet
  facet normal -0.319289 -0.947657 -0.000000
    outer loop
      vertex 52.409454 89.644890 15.000000
      vertex 51.896404 89.817749 0.000000
      vertex 52.409454 89.644890 0.000000
    endloop
  endfacet
  facet normal -0.419892 -0.907574 0.000000
    outer loop
      vertex 52.900806 89.417564 15.000000
      vertex 52.409454 89.644890 15.000000
      vertex 52.409454 89.644890 0.000000
    endloop
  endfacet
  facet normal -0.419892 -0.907574 -0.000000
    outer loop
      vertex 52.900806 89.417564 15.000000
      vertex 52.409454 89.644890 0.000000
      vertex 52.900806 89.417564 0.000000
    endloop
  endfacet
  facet normal -0.515554 -0.856857 0.000000
    outer loop
      vertex 53.364697 89.138451 15.000000
      vertex 52.900806 89.417564 15.000000
      vertex 52.900806 89.417564 0.000000
    endloop
  endfacet
  facet normal -0.515554 -0.856857 -0.000000
    outer loop
      vertex 53.364697 89.138451 15.000000
      vertex 52.900806 89.417564 0.000000
      vertex 53.364697 89.138451 0.000000
    endloop
  endfacet
  facet normal -0.605182 -0.796087 0.000000
    outer loop
      vertex 53.795696 88.810806 15.000000
      vertex 53.364697 89.138451 15.000000
      vertex 53.364697 89.138451 0.000000
    endloop
  endfacet
  facet normal -0.605182 -0.796087 -0.000000
    outer loop
      vertex 53.795696 88.810806 15.000000
      vertex 53.364697 89.138451 0.000000
      vertex 53.795696 88.810806 0.000000
    endloop
  endfacet
  facet normal -0.687696 -0.725999 0.000000
    outer loop
      vertex 54.188740 88.438499 15.000000
      vertex 53.795696 88.810806 15.000000
      vertex 53.795696 88.810806 0.000000
    endloop
  endfacet
  facet normal -0.687696 -0.725999 -0.000000
    outer loop
      vertex 54.188740 88.438499 15.000000
      vertex 53.795696 88.810806 0.000000
      vertex 54.188740 88.438499 0.000000
    endloop
  endfacet
  facet normal -0.762161 -0.647387 0.000000
    outer loop
      vertex 54.539230 88.025871 15.000000
      vertex 54.188740 88.438499 15.000000
      vertex 54.188740 88.438499 0.000000
    endloop
  endfacet
  facet normal -0.762161 -0.647387 -0.000000
    outer loop
      vertex 54.539230 88.025871 15.000000
      vertex 54.188740 88.438499 0.000000
      vertex 54.539230 88.025871 0.000000
    endloop
  endfacet
  facet normal -0.827693 -0.561181 0.000000
    outer loop
      vertex 54.843048 87.577766 15.000000
      vertex 54.539230 88.025871 15.000000
      vertex 54.539230 88.025871 0.000000
    endloop
  endfacet
  facet normal -0.827693 -0.561181 -0.000000
    outer loop
      vertex 54.843048 87.577766 15.000000
      vertex 54.539230 88.025871 0.000000
      vertex 54.843048 87.577766 0.000000
    endloop
  endfacet
  facet normal -0.883508 -0.468417 0.000000
    outer loop
      vertex 55.096642 87.099449 15.000000
      vertex 54.843048 87.577766 15.000000
      vertex 54.843048 87.577766 0.000000
    endloop
  endfacet
  facet normal -0.883508 -0.468417 -0.000000
    outer loop
      vertex 55.096642 87.099449 15.000000
      vertex 54.843048 87.577766 0.000000
      vertex 55.096642 87.099449 0.000000
    endloop
  endfacet
  facet normal -0.928978 -0.370134 0.000000
    outer loop
      vertex 55.297028 86.596512 15.000000
      vertex 55.096642 87.099449 15.000000
      vertex 55.096642 87.099449 0.000000
    endloop
  endfacet
  facet normal -0.928978 -0.370134 -0.000000
    outer loop
      vertex 55.297028 86.596512 15.000000
      vertex 55.096642 87.099449 0.000000
      vertex 55.297028 86.596512 0.000000
    endloop
  endfacet
  facet normal -0.963549 -0.267532 0.000000
    outer loop
      vertex 55.441868 86.074852 15.000000
      vertex 55.297028 86.596512 15.000000
      vertex 55.297028 86.596512 0.000000
    endloop
  endfacet
  facet normal -0.963549 -0.267532 -0.000000
    outer loop
      vertex 55.441868 86.074852 15.000000
      vertex 55.297028 86.596512 0.000000
      vertex 55.441868 86.074852 0.000000
    endloop
  endfacet
  facet normal -0.986827 -0.161780 0.000000
    outer loop
      vertex 55.529453 85.540596 15.000000
      vertex 55.441868 86.074852 15.000000
      vertex 55.441868 86.074852 0.000000
    endloop
  endfacet
  facet normal -0.986827 -0.161780 -0.000000
    outer loop
      vertex 55.529453 85.540596 15.000000
      vertex 55.441868 86.074852 0.000000
      vertex 55.529453 85.540596 0.000000
    endloop
  endfacet
  facet normal -0.998534 -0.054135 0.000000
    outer loop
      vertex 55.558762 85.000000 15.000000
      vertex 55.529453 85.540596 15.000000
      vertex 55.529453 85.540596 0.000000
    endloop
  endfacet
  facet normal -0.998534 -0.054135 -0.000000
    outer loop
      vertex 55.558762 85.000000 15.000000
      vertex 55.529453 85.540596 0.000000
      vertex 55.558762 85.000000 0.000000
    endloop
  endfacet
  facet normal -0.998534 0.054135 0.000000
    outer loop
      vertex 55.529453 84.459404 15.000000
      vertex 55.558762 85.000000 15.000000
      vertex 55.558762 85.000000 0.000000
    endloop
  endfacet
  facet normal -0.998534 0.054135 0.000000
    outer loop
      vertex 55.529453 84.459404 15.000000
      vertex 55.558762 85.000000 0.000000
      vertex 55.529453 84.459404 0.000000
    endloop
  endfacet
  facet normal -0.986827 0.161780 0.000000
    outer loop
      vertex 55.441868 83.925148 15.000000
      vertex 55.529453 84.459404 15.000000
      vertex 55.529453 84.459404 0.000000
    endloop
  endfacet
  facet normal -0.986827 0.161780 0.000000
    outer loop
      vertex 55.441868 83.925148 15.000000
      vertex 55.529453 84.459404 0.000000
      vertex 55.441868 83.925148 0.000000
    endloop
  endfacet
  facet normal -0.963549 0.267532 0.000000
    outer loop
      vertex 55.297028 83.403488 15.000000
      vertex 55.441868 83.925148 15.000000
      vertex 55.441868 83.925148 0.000000
    endloop
  endfacet
  facet normal -0.963549 0.267532 0.000000
    outer loop
      vertex 55.297028 83.403488 15.000000
      vertex 55.441868 83.925148 0.000000
      vertex 55.297028 83.403488 0.000000
    endloop
  endfacet
  facet normal -0.928978 0.370134 0.000000
    outer loop
      vertex 55.096642 82.900551 15.000000
      vertex 55.297028 83.403488 15.000000
      vertex 55.297028 83.403488 0.000000
    endloop
  endfacet
  facet normal -0.928978 0.370134 0.000000
    outer loop
      vertex 55.096642 82.900551 15.000000
      vertex 55.297028 83.403488 0.000000
      vertex 55.096642 82.900551 0.000000
    endloop
  endfacet
  facet normal -0.883508 0.468417 0.000000
    outer loop
      vertex 54.843048 82.422234 15.000000
      vertex 55.096642 82.900551 15.000000
      vertex 55.096642 82.900551 0.000000
    endloop
  endfacet
  facet normal -0.883508 0.468417 0.000000
    outer loop
      vertex 54.843048 82.422234 15.000000
      vertex 55.096642 82.900551 0.000000
      vertex 54.843048 82.422234 0.000000
    endloop
  endfacet
  facet normal -0.827693 0.561181 0.000000
    outer loop
      vertex 54.539230 81.974129 15.000000
      vertex 54.843048 82.422234 15.000000
      vertex 54.843048 82.422234 0.000000
    endloop
  endfacet
  facet normal -0.827693 0.561181 0.000000
    outer loop
      vertex 54.539230 81.974129 15.000000
      vertex 54.843048 82.422234 0.000000
      vertex 54.539230 81.974129 0.000000
    endloop
  endfacet
  facet normal -0.762155 0.647394 0.000000
    outer loop
      vertex 54.188740 81.561508 15.000000
      vertex 54.539230 81.974129 15.000000
      vertex 54.539230 81.974129 0.000000
    endloop
  endfacet
  facet normal -0.762155 0.647394 0.000000
    outer loop
      vertex 54.188740 81.561508 15.000000
      vertex 54.539230 81.974129 0.000000
      vertex 54.188740 81.561508 0.000000
    endloop
  endfacet
  facet normal -0.687703 0.725992 0.000000
    outer loop
      vertex 53.795696 81.189194 15.000000
      vertex 54.188740 81.561508 15.000000
      vertex 54.188740 81.561508 0.000000
    endloop
  endfacet
  facet normal -0.687703 0.725992 0.000000
    outer loop
      vertex 53.795696 81.189194 15.000000
      vertex 54.188740 81.561508 0.000000
      vertex 53.795696 81.189194 0.000000
    endloop
  endfacet
  facet normal -0.605173 0.796094 0.000000
    outer loop
      vertex 53.364697 80.861557 15.000000
      vertex 53.795696 81.189194 15.000000
      vertex 53.795696 81.189194 0.000000
    endloop
  endfacet
  facet normal -0.605173 0.796094 0.000000
    outer loop
      vertex 53.364697 80.861557 15.000000
      vertex 53.795696 81.189194 0.000000
      vertex 53.364697 80.861557 0.000000
    endloop
  endfacet
  facet normal -0.515554 0.856857 0.000000
    outer loop
      vertex 52.900806 80.582443 15.000000
      vertex 53.364697 80.861557 15.000000
      vertex 53.364697 80.861557 0.000000
    endloop
  endfacet
  facet normal -0.515554 0.856857 0.000000
    outer loop
      vertex 52.900806 80.582443 15.000000
      vertex 53.364697 80.861557 0.000000
      vertex 52.900806 80.582443 0.000000
    endloop
  endfacet
  facet normal -0.419892 0.907574 0.000000
    outer loop
      vertex 52.409454 80.355118 15.000000
      vertex 52.900806 80.582443 15.000000
      vertex 52.900806 80.582443 0.000000
    endloop
  endfacet
  facet normal -0.419892 0.907574 0.000000
    outer loop
      vertex 52.409454 80.355118 15.000000
      vertex 52.900806 80.582443 0.000000
      vertex 52.409454 80.355118 0.000000
    endloop
  endfacet
  facet normal -0.319314 0.947649 0.000000
    outer loop
      vertex 51.896404 80.182243 15.000000
      vertex 52.409454 80.355118 15.000000
      vertex 52.409454 80.355118 0.000000
    endloop
  endfacet
  facet normal -0.319314 0.947649 0.000000
    outer loop
      vertex 51.896404 80.182243 15.000000
      vertex 52.409454 80.355118 0.000000
      vertex 51.896404 80.182243 0.000000
    endloop
  endfacet
  facet normal -0.214951 0.976625 0.000000
    outer loop
      vertex 51.367676 80.065872 15.000000
      vertex 51.896404 80.182243 15.000000
      vertex 51.896404 80.182243 0.000000
    endloop
  endfacet
  facet normal -0.214951 0.976625 0.000000
    outer loop
      vertex 51.367676 80.065872 15.000000
      vertex 51.896404 80.182243 0.000000
      vertex 51.367676 80.065872 0.000000
    endloop
  endfacet
  facet normal -0.108130 0.994137 0.000000
    outer loop
      vertex 50.829460 80.007332 15.000000
      vertex 51.367676 80.065872 15.000000
      vertex 51.367676 80.065872 0.000000
    endloop
  endfacet
  facet normal -0.108130 0.994137 0.000000
    outer loop
      vertex 50.829460 80.007332 15.000000
      vertex 51.367676 80.065872 0.000000
      vertex 50.829460 80.007332 0.000000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 50.288071 80.007332 15.000000
      vertex 50.829460 80.007332 15.000000
      vertex 50.829460 80.007332 0.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 50.288071 80.007332 15.000000
      vertex 50.829460 80.007332 0.000000
      vertex 50.288071 80.007332 0.000000
    endloop
  endfacet
  facet normal 0.108130 0.994137 0.000000
    outer loop
      vertex 49.749855 80.065872 15.000000
      vertex 50.288071 80.007332 15.000000
      vertex 50.288071 80.007332 0.000000
    endloop
  endfacet
  facet normal 0.108130 0.994137 0.000000
    outer loop
      vertex 49.749855 80.065872 15.000000
      vertex 50.288071 80.007332 0.000000
      vertex 49.749855 80.065872 0.000000
    endloop
  endfacet
  facet normal 0.214948 0.976625 0.000000
    outer loop
      vertex 49.221119 80.182243 15.000000
      vertex 49.749855 80.065872 15.000000
      vertex 49.749855 80.065872 0.000000
    endloop
  endfacet
  facet normal 0.214948 0.976625 0.000000
    outer loop
      vertex 49.221119 80.182243 15.000000
      vertex 49.749855 80.065872 0.000000
      vertex 49.221119 80.182243 0.000000
    endloop
  endfacet
  facet normal 0.319317 0.947648 0.000000
    outer loop
      vertex 48.708073 80.355118 15.000000
      vertex 49.221119 80.182243 15.000000
      vertex 49.221119 80.182243 0.000000
    endloop
  endfacet
  facet normal 0.319317 0.947648 0.000000
    outer loop
      vertex 48.708073 80.355118 15.000000
      vertex 49.221119 80.182243 0.000000
      vertex 48.708073 80.355118 0.000000
    endloop
  endfacet
  facet normal 0.419894 0.907573 0.000000
    outer loop
      vertex 48.216724 80.582443 15.000000
      vertex 48.708073 80.355118 15.000000
      vertex 48.708073 80.355118 0.000000
    endloop
  endfacet
  facet normal 0.419894 0.907573 0.000000
    outer loop
      vertex 48.216724 80.582443 15.000000
      vertex 48.708073 80.355118 0.000000
      vertex 48.216724 80.582443 0.000000
    endloop
  endfacet
  facet normal 0.515548 0.856861 0.000000
    outer loop
      vertex 47.752827 80.861557 15.000000
      vertex 48.216724 80.582443 15.000000
      vertex 48.216724 80.582443 0.000000
    endloop
  endfacet
  facet normal 0.515548 0.856861 0.000000
    outer loop
      vertex 47.752827 80.861557 15.000000
      vertex 48.216724 80.582443 0.000000
      vertex 47.752827 80.861557 0.000000
    endloop
  endfacet
  facet normal 0.605180 0.796089 0.000000
    outer loop
      vertex 47.321835 81.189194 15.000000
      vertex 47.752827 80.861557 15.000000
      vertex 47.752827 80.861557 0.000000
    endloop
  endfacet
  facet normal 0.605180 0.796089 0.000000
    outer loop
      vertex 47.321835 81.189194 15.000000
      vertex 47.752827 80.861557 0.000000
      vertex 47.321835 81.189194 0.000000
    endloop
  endfacet
  facet normal 0.687700 0.725995 0.000000
    outer loop
      vertex 46.928787 81.561508 15.000000
      vertex 47.321835 81.189194 15.000000
      vertex 47.321835 81.189194 0.000000
    endloop
  endfacet
  facet normal 0.687700 0.725995 0.000000
    outer loop
      vertex 46.928787 81.561508 15.000000
      vertex 47.321835 81.189194 0.000000
      vertex 46.928787 81.561508 0.000000
    endloop
  endfacet
  facet normal 0.762159 0.647390 0.000000
    outer loop
      vertex 46.578300 81.974129 15.000000
      vertex 46.928787 81.561508 15.000000
      vertex 46.928787 81.561508 0.000000
    endloop
  endfacet
  facet normal 0.762159 0.647390 0.000000
    outer loop
      vertex 46.578300 81.974129 15.000000
      vertex 46.928787 81.561508 0.000000
      vertex 46.578300 81.974129 0.000000
    endloop
  endfacet
  facet normal 0.827690 0.561186 0.000000
    outer loop
      vertex 46.274479 82.422234 15.000000
      vertex 46.578300 81.974129 15.000000
      vertex 46.578300 81.974129 0.000000
    endloop
  endfacet
  facet normal 0.827690 0.561186 0.000000
    outer loop
      vertex 46.274479 82.422234 15.000000
      vertex 46.578300 81.974129 0.000000
      vertex 46.274479 82.422234 0.000000
    endloop
  endfacet
  facet normal 0.883511 0.468411 0.000000
    outer loop
      vertex 46.020889 82.900551 15.000000
      vertex 46.274479 82.422234 15.000000
      vertex 46.274479 82.422234 0.000000
    endloop
  endfacet
  facet normal 0.883511 0.468411 0.000000
    outer loop
      vertex 46.020889 82.900551 15.000000
      vertex 46.274479 82.422234 0.000000
      vertex 46.020889 82.900551 0.000000
    endloop
  endfacet
  facet normal 0.928973 0.370146 0.000000
    outer loop
      vertex 45.820496 83.403488 15.000000
      vertex 46.020889 82.900551 15.000000
      vertex 46.020889 82.900551 0.000000
    endloop
  endfacet
  facet normal 0.928973 0.370146 0.000000
    outer loop
      vertex 45.820496 83.403488 15.000000
      vertex 46.020889 82.900551 0.000000
      vertex 45.820496 83.403488 0.000000
    endloop
  endfacet
  facet normal 0.963553 0.267519 0.000000
    outer loop
      vertex 45.675663 83.925148 15.000000
      vertex 45.820496 83.403488 15.000000
      vertex 45.820496 83.403488 0.000000
    endloop
  endfacet
  facet normal 0.963553 0.267519 0.000000
    outer loop
      vertex 45.675663 83.925148 15.000000
      vertex 45.820496 83.403488 0.000000
      vertex 45.675663 83.925148 0.000000
    endloop
  endfacet
  facet normal 0.986826 0.161786 0.000000
    outer loop
      vertex 45.588074 84.459404 15.000000
      vertex 45.675663 83.925148 15.000000
      vertex 45.675663 83.925148 0.000000
    endloop
  endfacet
  facet normal 0.986826 0.161786 0.000000
    outer loop
      vertex 45.588074 84.459404 15.000000
      vertex 45.675663 83.925148 0.000000
      vertex 45.588074 84.459404 0.000000
    endloop
  endfacet
  facet normal 0.998534 0.054135 0.000000
    outer loop
      vertex 45.558765 85.000000 15.000000
      vertex 45.588074 84.459404 15.000000
      vertex 45.588074 84.459404 0.000000
    endloop
  endfacet
  facet normal 0.998534 0.054135 0.000000
    outer loop
      vertex 45.558765 85.000000 15.000000
      vertex 45.588074 84.459404 0.000000
      vertex 45.558765 85.000000 0.000000
    endloop
  endfacet
  facet normal 0.772512 0.635000 0.000000
    outer loop
      vertex 43.606743 3.977030 15.000000
      vertex 46.875835 0.000000 15.000000
      vertex 46.875835 0.000000 0.000000
    endloop
  endfacet
  facet normal 0.772512 0.635000 0.000000
    outer loop
      vertex 43.606743 3.977030 15.000000
      vertex 46.875835 0.000000 0.000000
      vertex 43.606743 3.977030 0.000000
    endloop
  endfacet
  facet normal 0.835277 0.549830 0.000000
    outer loop
      vertex 40.776123 8.277181 15.000000
      vertex 43.606743 3.977030 15.000000
      vertex 43.606743 3.977030 0.000000
    endloop
  endfacet
  facet normal 0.835277 0.549830 0.000000
    outer loop
      vertex 40.776123 8.277181 15.000000
      vertex 43.606743 3.977030 0.000000
      vertex 40.776123 8.277181 0.000000
    endloop
  endfacet
  facet normal 0.888691 0.458506 0.000000
    outer loop
      vertex 38.415653 12.852320 15.000000
      vertex 40.776123 8.277181 15.000000
      vertex 40.776123 8.277181 0.000000
    endloop
  endfacet
  facet normal 0.888691 0.458506 0.000000
    outer loop
      vertex 38.415653 12.852320 15.000000
      vertex 40.776123 8.277181 0.000000
      vertex 38.415653 12.852320 0.000000
    endloop
  endfacet
  facet normal 0.932159 0.362050 0.000000
    outer loop
      vertex 36.551758 17.651237 15.000000
      vertex 38.415653 12.852320 15.000000
      vertex 38.415653 12.852320 0.000000
    endloop
  endfacet
  facet normal 0.932159 0.362050 0.000000
    outer loop
      vertex 36.551758 17.651237 15.000000
      vertex 38.415653 12.852320 0.000000
      vertex 36.551758 17.651237 0.000000
    endloop
  endfacet
  facet normal 0.965192 0.261542 0.000000
    outer loop
      vertex 35.205296 22.620216 15.000000
      vertex 36.551758 17.651237 15.000000
      vertex 36.551758 17.651237 0.000000
    endloop
  endfacet
  facet normal 0.965192 0.261542 0.000000
    outer loop
      vertex 35.205296 22.620216 15.000000
      vertex 36.551758 17.651237 0.000000
      vertex 35.205296 22.620216 0.000000
    endloop
  endfacet
  facet normal 0.987422 0.158104 0.000000
    outer loop
      vertex 34.391346 27.703640 15.000000
      vertex 35.205296 22.620216 15.000000
      vertex 35.205296 22.620216 0.000000
    endloop
  endfacet
  facet normal 0.987422 0.158104 0.000000
    outer loop
      vertex 34.391346 27.703640 15.000000
      vertex 35.205296 22.620216 0.000000
      vertex 34.391346 27.703640 0.000000
    endloop
  endfacet
  facet normal 0.998600 0.052899 0.000000
    outer loop
      vertex 34.119015 32.844608 15.000000
      vertex 34.391346 27.703640 15.000000
      vertex 34.391346 27.703640 0.000000
    endloop
  endfacet
  facet normal 0.998600 0.052899 0.000000
    outer loop
      vertex 34.119015 32.844608 15.000000
      vertex 34.391346 27.703640 0.000000
      vertex 34.119015 32.844608 0.000000
    endloop
  endfacet
  facet normal 0.998600 -0.052899 0.000000
    outer loop
      vertex 34.391346 37.985573 15.000000
      vertex 34.119015 32.844608 15.000000
      vertex 34.119015 32.844608 0.000000
    endloop
  endfacet
  facet normal 0.998600 -0.052899 0.000000
    outer loop
      vertex 34.391346 37.985573 15.000000
      vertex 34.119015 32.844608 0.000000
      vertex 34.391346 37.985573 0.000000
    endloop
  endfacet
  facet normal 0.987422 -0.158104 0.000000
    outer loop
      vertex 35.205296 43.068996 15.000000
      vertex 34.391346 37.985573 15.000000
      vertex 34.391346 37.985573 0.000000
    endloop
  endfacet
  facet normal 0.987422 -0.158104 0.000000
    outer loop
      vertex 35.205296 43.068996 15.000000
      vertex 34.391346 37.985573 0.000000
      vertex 35.205296 43.068996 0.000000
    endloop
  endfacet
  facet normal 0.965192 -0.261541 0.000000
    outer loop
      vertex 36.551758 48.037979 15.000000
      vertex 35.205296 43.068996 15.000000
      vertex 35.205296 43.068996 0.000000
    endloop
  endfacet
  facet normal 0.965192 -0.261541 0.000000
    outer loop
      vertex 36.551758 48.037979 15.000000
      vertex 35.205296 43.068996 0.000000
      vertex 36.551758 48.037979 0.000000
    endloop
  endfacet
  facet normal 0.932159 -0.362050 0.000000
    outer loop
      vertex 38.415653 52.836895 15.000000
      vertex 36.551758 48.037979 15.000000
      vertex 36.551758 48.037979 0.000000
    endloop
  endfacet
  facet normal 0.932159 -0.362050 0.000000
    outer loop
      vertex 38.415653 52.836895 15.000000
      vertex 36.551758 48.037979 0.000000
      vertex 38.415653 52.836895 0.000000
    endloop
  endfacet
  facet normal 0.888691 -0.458506 0.000000
    outer loop
      vertex 40.776123 57.412037 15.000000
      vertex 38.415653 52.836895 15.000000
      vertex 38.415653 52.836895 0.000000
    endloop
  endfacet
  facet normal 0.888691 -0.458506 0.000000
    outer loop
      vertex 40.776123 57.412037 15.000000
      vertex 38.415653 52.836895 0.000000
      vertex 40.776123 57.412037 0.000000
    endloop
  endfacet
  facet normal 0.835277 -0.549830 0.000000
    outer loop
      vertex 43.606743 61.712185 15.000000
      vertex 40.776123 57.412037 15.000000
      vertex 40.776123 57.412037 0.000000
    endloop
  endfacet
  facet normal 0.835277 -0.549830 0.000000
    outer loop
      vertex 43.606743 61.712185 15.000000
      vertex 40.776123 57.412037 0.000000
      vertex 43.606743 61.712185 0.000000
    endloop
  endfacet
  facet normal 0.772512 -0.635000 0.000000
    outer loop
      vertex 46.875835 65.689217 15.000000
      vertex 43.606743 61.712185 15.000000
      vertex 43.606743 61.712185 0.000000
    endloop
  endfacet
  facet normal 0.772512 -0.635000 0.000000
    outer loop
      vertex 46.875835 65.689217 15.000000
      vertex 43.606743 61.712185 0.000000
      vertex 46.875835 65.689217 0.000000
    endloop
  endfacet
  facet normal 0.998533 -0.054149 0.000000
    outer loop
      vertex -89.527679 0.432476 15.000000
      vertex -89.551132 -0.000000 15.000000
      vertex -89.551132 -0.000000 0.000000
    endloop
  endfacet
  facet normal 0.998533 -0.054149 0.000000
    outer loop
      vertex -89.527679 0.432476 15.000000
      vertex -89.551132 -0.000000 0.000000
      vertex -89.527679 0.432476 0.000000
    endloop
  endfacet
  facet normal 0.986830 -0.161762 0.000000
    outer loop
      vertex -89.457619 0.859882 15.000000
      vertex -89.527679 0.432476 15.000000
      vertex -89.527679 0.432476 0.000000
    endloop
  endfacet
  facet normal 0.986830 -0.161762 0.000000
    outer loop
      vertex -89.457619 0.859882 15.000000
      vertex -89.527679 0.432476 0.000000
      vertex -89.457619 0.859882 0.000000
    endloop
  endfacet
  facet normal 0.963547 -0.267541 0.000000
    outer loop
      vertex -89.341743 1.277206 15.000000
      vertex -89.457619 0.859882 15.000000
      vertex -89.457619 0.859882 0.000000
    endloop
  endfacet
  facet normal 0.963547 -0.267541 0.000000
    outer loop
      vertex -89.341743 1.277206 15.000000
      vertex -89.457619 0.859882 0.000000
      vertex -89.341743 1.277206 0.000000
    endloop
  endfacet
  facet normal 0.928972 -0.370149 0.000000
    outer loop
      vertex -89.181427 1.679556 15.000000
      vertex -89.341743 1.277206 15.000000
      vertex -89.341743 1.277206 0.000000
    endloop
  endfacet
  facet normal 0.928972 -0.370149 0.000000
    outer loop
      vertex -89.181427 1.679556 15.000000
      vertex -89.341743 1.277206 0.000000
      vertex -89.181427 1.679556 0.000000
    endloop
  endfacet
  facet normal 0.883519 -0.468395 0.000000
    outer loop
      vertex -88.978561 2.062216 15.000000
      vertex -89.181427 1.679556 15.000000
      vertex -89.181427 1.679556 0.000000
    endloop
  endfacet
  facet normal 0.883519 -0.468395 0.000000
    outer loop
      vertex -88.978561 2.062216 15.000000
      vertex -89.181427 1.679556 0.000000
      vertex -88.978561 2.062216 0.000000
    endloop
  endfacet
  facet normal 0.827688 -0.561188 0.000000
    outer loop
      vertex -88.735504 2.420697 15.000000
      vertex -88.978561 2.062216 15.000000
      vertex -88.978561 2.062216 0.000000
    endloop
  endfacet
  facet normal 0.827688 -0.561188 0.000000
    outer loop
      vertex -88.735504 2.420697 15.000000
      vertex -88.978561 2.062216 0.000000
      vertex -88.735504 2.420697 0.000000
    endloop
  endfacet
  facet normal 0.762156 -0.647393 0.000000
    outer loop
      vertex -88.455109 2.750798 15.000000
      vertex -88.735504 2.420697 15.000000
      vertex -88.735504 2.420697 0.000000
    endloop
  endfacet
  facet normal 0.762156 -0.647393 0.000000
    outer loop
      vertex -88.455109 2.750798 15.000000
      vertex -88.735504 2.420697 0.000000
      vertex -88.455109 2.750798 0.000000
    endloop
  endfacet
  facet normal 0.687698 -0.725997 0.000000
    outer loop
      vertex -88.140671 3.048648 15.000000
      vertex -88.455109 2.750798 15.000000
      vertex -88.455109 2.750798 0.000000
    endloop
  endfacet
  facet normal 0.687698 -0.725997 0.000000
    outer loop
      vertex -88.140671 3.048648 15.000000
      vertex -88.455109 2.750798 0.000000
      vertex -88.140671 3.048648 0.000000
    endloop
  endfacet
  facet normal 0.605185 -0.796085 0.000000
    outer loop
      vertex -87.795883 3.310756 15.000000
      vertex -88.140671 3.048648 15.000000
      vertex -88.140671 3.048648 0.000000
    endloop
  endfacet
  facet normal 0.605185 -0.796085 0.000000
    outer loop
      vertex -87.795883 3.310756 15.000000
      vertex -88.140671 3.048648 0.000000
      vertex -87.795883 3.310756 0.000000
    endloop
  endfacet
  facet normal 0.515544 -0.856863 0.000000
    outer loop
      vertex -87.424759 3.534048 15.000000
      vertex -87.795883 3.310756 15.000000
      vertex -87.795883 3.310756 0.000000
    endloop
  endfacet
  facet normal 0.515544 -0.856863 0.000000
    outer loop
      vertex -87.424759 3.534048 15.000000
      vertex -87.795883 3.310756 0.000000
      vertex -87.424759 3.534048 0.000000
    endloop
  endfacet
  facet normal 0.419896 -0.907572 0.000000
    outer loop
      vertex -87.031685 3.715907 15.000000
      vertex -87.424759 3.534048 15.000000
      vertex -87.424759 3.534048 0.000000
    endloop
  endfacet
  facet normal 0.419896 -0.907572 0.000000
    outer loop
      vertex -87.031685 3.715907 15.000000
      vertex -87.424759 3.534048 0.000000
      vertex -87.031685 3.715907 0.000000
    endloop
  endfacet
  facet normal 0.319302 -0.947653 0.000000
    outer loop
      vertex -86.621246 3.854200 15.000000
      vertex -87.031685 3.715907 15.000000
      vertex -87.031685 3.715907 0.000000
    endloop
  endfacet
  facet normal 0.319302 -0.947653 0.000000
    outer loop
      vertex -86.621246 3.854200 15.000000
      vertex -87.031685 3.715907 0.000000
      vertex -86.621246 3.854200 0.000000
    endloop
  endfacet
  facet normal 0.214972 -0.976620 0.000000
    outer loop
      vertex -86.198265 3.947306 15.000000
      vertex -86.621246 3.854200 15.000000
      vertex -86.621246 3.854200 0.000000
    endloop
  endfacet
  facet normal 0.214972 -0.976620 0.000000
    outer loop
      vertex -86.198265 3.947306 15.000000
      vertex -86.621246 3.854200 0.000000
      vertex -86.198265 3.947306 0.000000
    endloop
  endfacet
  facet normal 0.108118 -0.994138 0.000000
    outer loop
      vertex -85.767685 3.994134 15.000000
      vertex -86.198265 3.947306 15.000000
      vertex -86.198265 3.947306 0.000000
    endloop
  endfacet
  facet normal 0.108118 -0.994138 0.000000
    outer loop
      vertex -85.767685 3.994134 15.000000
      vertex -86.198265 3.947306 0.000000
      vertex -85.767685 3.994134 0.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex -85.334579 3.994134 15.000000
      vertex -85.767685 3.994134 15.000000
      vertex -85.767685 3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex -85.334579 3.994134 15.000000
      vertex -85.767685 3.994134 0.000000
      vertex -85.334579 3.994134 0.000000
    endloop
  endfacet
  facet normal -0.108120 -0.994138 0.000000
    outer loop
      vertex -84.904007 3.947306 15.000000
      vertex -85.334579 3.994134 15.000000
      vertex -85.334579 3.994134 0.000000
    endloop
  endfacet
  facet normal -0.108120 -0.994138 -0.000000
    outer loop
      vertex -84.904007 3.947306 15.000000
      vertex -85.334579 3.994134 0.000000
      vertex -84.904007 3.947306 0.000000
    endloop
  endfacet
  facet normal -0.214968 -0.976621 0.000000
    outer loop
      vertex -84.481018 3.854200 15.000000
      vertex -84.904007 3.947306 15.000000
      vertex -84.904007 3.947306 0.000000
    endloop
  endfacet
  facet normal -0.214968 -0.976621 -0.000000
    outer loop
      vertex -84.481018 3.854200 15.000000
      vertex -84.904007 3.947306 0.000000
      vertex -84.481018 3.854200 0.000000
    endloop
  endfacet
  facet normal -0.319302 -0.947653 0.000000
    outer loop
      vertex -84.070580 3.715907 15.000000
      vertex -84.481018 3.854200 15.000000
      vertex -84.481018 3.854200 0.000000
    endloop
  endfacet
  facet normal -0.319302 -0.947653 -0.000000
    outer loop
      vertex -84.070580 3.715907 15.000000
      vertex -84.481018 3.854200 0.000000
      vertex -84.070580 3.715907 0.000000
    endloop
  endfacet
  facet normal -0.419889 -0.907575 0.000000
    outer loop
      vertex -83.677498 3.534048 15.000000
      vertex -84.070580 3.715907 15.000000
      vertex -84.070580 3.715907 0.000000
    endloop
  endfacet
  facet normal -0.419889 -0.907575 -0.000000
    outer loop
      vertex -83.677498 3.534048 15.000000
      vertex -84.070580 3.715907 0.000000
      vertex -83.677498 3.534048 0.000000
    endloop
  endfacet
  facet normal -0.515559 -0.856854 0.000000
    outer loop
      vertex -83.306389 3.310756 15.000000
      vertex -83.677498 3.534048 15.000000
      vertex -83.677498 3.534048 0.000000
    endloop
  endfacet
  facet normal -0.515559 -0.856854 -0.000000
    outer loop
      vertex -83.306389 3.310756 15.000000
      vertex -83.677498 3.534048 0.000000
      vertex -83.306389 3.310756 0.000000
    endloop
  endfacet
  facet normal -0.605168 -0.796098 0.000000
    outer loop
      vertex -82.961586 3.048648 15.000000
      vertex -83.306389 3.310756 15.000000
      vertex -83.306389 3.310756 0.000000
    endloop
  endfacet
  facet normal -0.605168 -0.796098 -0.000000
    outer loop
      vertex -82.961586 3.048648 15.000000
      vertex -83.306389 3.310756 0.000000
      vertex -82.961586 3.048648 0.000000
    endloop
  endfacet
  facet normal -0.687707 -0.725989 0.000000
    outer loop
      vertex -82.647156 2.750798 15.000000
      vertex -82.961586 3.048648 15.000000
      vertex -82.961586 3.048648 0.000000
    endloop
  endfacet
  facet normal -0.687707 -0.725989 -0.000000
    outer loop
      vertex -82.647156 2.750798 15.000000
      vertex -82.961586 3.048648 0.000000
      vertex -82.647156 2.750798 0.000000
    endloop
  endfacet
  facet normal -0.762156 -0.647393 0.000000
    outer loop
      vertex -82.366760 2.420697 15.000000
      vertex -82.647156 2.750798 15.000000
      vertex -82.647156 2.750798 0.000000
    endloop
  endfacet
  facet normal -0.762156 -0.647393 -0.000000
    outer loop
      vertex -82.366760 2.420697 15.000000
      vertex -82.647156 2.750798 0.000000
      vertex -82.366760 2.420697 0.000000
    endloop
  endfacet
  facet normal -0.827688 -0.561188 0.000000
    outer loop
      vertex -82.123703 2.062216 15.000000
      vertex -82.366760 2.420697 15.000000
      vertex -82.366760 2.420697 0.000000
    endloop
  endfacet
  facet normal -0.827688 -0.561188 -0.000000
    outer loop
      vertex -82.123703 2.062216 15.000000
      vertex -82.366760 2.420697 0.000000
      vertex -82.123703 2.062216 0.000000
    endloop
  endfacet
  facet normal -0.883512 -0.468409 0.000000
    outer loop
      vertex -81.920830 1.679556 15.000000
      vertex -82.123703 2.062216 15.000000
      vertex -82.123703 2.062216 0.000000
    endloop
  endfacet
  facet normal -0.883512 -0.468409 -0.000000
    outer loop
      vertex -81.920830 1.679556 15.000000
      vertex -82.123703 2.062216 0.000000
      vertex -81.920830 1.679556 0.000000
    endloop
  endfacet
  facet normal -0.928979 -0.370134 0.000000
    outer loop
      vertex -81.760521 1.277206 15.000000
      vertex -81.920830 1.679556 15.000000
      vertex -81.920830 1.679556 0.000000
    endloop
  endfacet
  facet normal -0.928979 -0.370134 -0.000000
    outer loop
      vertex -81.760521 1.277206 15.000000
      vertex -81.920830 1.679556 0.000000
      vertex -81.760521 1.277206 0.000000
    endloop
  endfacet
  facet normal -0.963547 -0.267541 0.000000
    outer loop
      vertex -81.644646 0.859882 15.000000
      vertex -81.760521 1.277206 15.000000
      vertex -81.760521 1.277206 0.000000
    endloop
  endfacet
  facet normal -0.963547 -0.267541 -0.000000
    outer loop
      vertex -81.644646 0.859882 15.000000
      vertex -81.760521 1.277206 0.000000
      vertex -81.644646 0.859882 0.000000
    endloop
  endfacet
  facet normal -0.986830 -0.161762 0.000000
    outer loop
      vertex -81.574585 0.432476 15.000000
      vertex -81.644646 0.859882 15.000000
      vertex -81.644646 0.859882 0.000000
    endloop
  endfacet
  facet normal -0.986830 -0.161762 -0.000000
    outer loop
      vertex -81.574585 0.432476 15.000000
      vertex -81.644646 0.859882 0.000000
      vertex -81.574585 0.432476 0.000000
    endloop
  endfacet
  facet normal -0.998533 -0.054149 0.000000
    outer loop
      vertex -81.551132 -0.000000 15.000000
      vertex -81.574585 0.432476 15.000000
      vertex -81.574585 0.432476 0.000000
    endloop
  endfacet
  facet normal -0.998533 -0.054149 -0.000000
    outer loop
      vertex -81.551132 -0.000000 15.000000
      vertex -81.574585 0.432476 0.000000
      vertex -81.551132 -0.000000 0.000000
    endloop
  endfacet
  facet normal -0.998533 0.054149 0.000000
    outer loop
      vertex -81.574585 -0.432476 15.000000
      vertex -81.551132 -0.000000 15.000000
      vertex -81.551132 -0.000000 0.000000
    endloop
  endfacet
  facet normal -0.998533 0.054149 0.000000
    outer loop
      vertex -81.574585 -0.432476 15.000000
      vertex -81.551132 -0.000000 0.000000
      vertex -81.574585 -0.432476 0.000000
    endloop
  endfacet
  facet normal -0.986830 0.161762 0.000000
    outer loop
      vertex -81.644646 -0.859882 15.000000
      vertex -81.574585 -0.432476 15.000000
      vertex -81.574585 -0.432476 0.000000
    endloop
  endfacet
  facet normal -0.986830 0.161762 0.000000
    outer loop
      vertex -81.644646 -0.859882 15.000000
      vertex -81.574585 -0.432476 0.000000
      vertex -81.644646 -0.859882 0.000000
    endloop
  endfacet
  facet normal -0.963547 0.267541 0.000000
    outer loop
      vertex -81.760521 -1.277206 15.000000
      vertex -81.644646 -0.859882 15.000000
      vertex -81.644646 -0.859882 0.000000
    endloop
  endfacet
  facet normal -0.963547 0.267541 0.000000
    outer loop
      vertex -81.760521 -1.277206 15.000000
      vertex -81.644646 -0.859882 0.000000
      vertex -81.760521 -1.277206 0.000000
    endloop
  endfacet
  facet normal -0.928979 0.370134 0.000000
    outer loop
      vertex -81.920830 -1.679556 15.000000
      vertex -81.760521 -1.277206 15.000000
      vertex -81.760521 -1.277206 0.000000
    endloop
  endfacet
  facet normal -0.928979 0.370134 0.000000
    outer loop
      vertex -81.920830 -1.679556 15.000000
      vertex -81.760521 -1.277206 0.000000
      vertex -81.920830 -1.679556 0.000000
    endloop
  endfacet
  facet normal -0.883512 0.468409 0.000000
    outer loop
      vertex -82.123703 -2.062216 15.000000
      vertex -81.920830 -1.679556 15.000000
      vertex -81.920830 -1.679556 0.000000
    endloop
  endfacet
  facet normal -0.883512 0.468409 0.000000
    outer loop
      vertex -82.123703 -2.062216 15.000000
      vertex -81.920830 -1.679556 0.000000
      vertex -82.123703 -2.062216 0.000000
    endloop
  endfacet
  facet normal -0.827688 0.561188 0.000000
    outer loop
      vertex -82.366760 -2.420697 15.000000
      vertex -82.123703 -2.062216 15.000000
      vertex -82.123703 -2.062216 0.000000
    endloop
  endfacet
  facet normal -0.827688 0.561188 0.000000
    outer loop
      vertex -82.366760 -2.420697 15.000000
      vertex -82.123703 -2.062216 0.000000
      vertex -82.366760 -2.420697 0.000000
    endloop
  endfacet
  facet normal -0.762156 0.647393 0.000000
    outer loop
      vertex -82.647156 -2.750798 15.000000
      vertex -82.366760 -2.420697 15.000000
      vertex -82.366760 -2.420697 0.000000
    endloop
  endfacet
  facet normal -0.762156 0.647393 0.000000
    outer loop
      vertex -82.647156 -2.750798 15.000000
      vertex -82.366760 -2.420697 0.000000
      vertex -82.647156 -2.750798 0.000000
    endloop
  endfacet
  facet normal -0.687707 0.725989 0.000000
    outer loop
      vertex -82.961586 -3.048648 15.000000
      vertex -82.647156 -2.750798 15.000000
      vertex -82.647156 -2.750798 0.000000
    endloop
  endfacet
  facet normal -0.687707 0.725989 0.000000
    outer loop
      vertex -82.961586 -3.048648 15.000000
      vertex -82.647156 -2.750798 0.000000
      vertex -82.961586 -3.048648 0.000000
    endloop
  endfacet
  facet normal -0.605168 0.796098 0.000000
    outer loop
      vertex -83.306389 -3.310756 15.000000
      vertex -82.961586 -3.048648 15.000000
      vertex -82.961586 -3.048648 0.000000
    endloop
  endfacet
  facet normal -0.605168 0.796098 0.000000
    outer loop
      vertex -83.306389 -3.310756 15.000000
      vertex -82.961586 -3.048648 0.000000
      vertex -83.306389 -3.310756 0.000000
    endloop
  endfacet
  facet normal -0.515559 0.856854 0.000000
    outer loop
      vertex -83.677498 -3.534048 15.000000
      vertex -83.306389 -3.310756 15.000000
      vertex -83.306389 -3.310756 0.000000
    endloop
  endfacet
  facet normal -0.515559 0.856854 0.000000
    outer loop
      vertex -83.677498 -3.534048 15.000000
      vertex -83.306389 -3.310756 0.000000
      vertex -83.677498 -3.534048 0.000000
    endloop
  endfacet
  facet normal -0.419889 0.907575 0.000000
    outer loop
      vertex -84.070580 -3.715907 15.000000
      vertex -83.677498 -3.534048 15.000000
      vertex -83.677498 -3.534048 0.000000
    endloop
  endfacet
  facet normal -0.419889 0.907575 0.000000
    outer loop
      vertex -84.070580 -3.715907 15.000000
      vertex -83.677498 -3.534048 0.000000
      vertex -84.070580 -3.715907 0.000000
    endloop
  endfacet
  facet normal -0.319302 0.947653 0.000000
    outer loop
      vertex -84.481018 -3.854200 15.000000
      vertex -84.070580 -3.715907 15.000000
      vertex -84.070580 -3.715907 0.000000
    endloop
  endfacet
  facet normal -0.319302 0.947653 0.000000
    outer loop
      vertex -84.481018 -3.854200 15.000000
      vertex -84.070580 -3.715907 0.000000
      vertex -84.481018 -3.854200 0.000000
    endloop
  endfacet
  facet normal -0.214968 0.976621 0.000000
    outer loop
      vertex -84.904007 -3.947306 15.000000
      vertex -84.481018 -3.854200 15.000000
      vertex -84.481018 -3.854200 0.000000
    endloop
  endfacet
  facet normal -0.214968 0.976621 0.000000
    outer loop
      vertex -84.904007 -3.947306 15.000000
      vertex -84.481018 -3.854200 0.000000
      vertex -84.904007 -3.947306 0.000000
    endloop
  endfacet
  facet normal -0.108120 0.994138 0.000000
    outer loop
      vertex -85.334579 -3.994134 15.000000
      vertex -84.904007 -3.947306 15.000000
      vertex -84.904007 -3.947306 0.000000
    endloop
  endfacet
  facet normal -0.108120 0.994138 0.000000
    outer loop
      vertex -85.334579 -3.994134 15.000000
      vertex -84.904007 -3.947306 0.000000
      vertex -85.334579 -3.994134 0.000000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -85.767685 -3.994134 15.000000
      vertex -85.334579 -3.994134 15.000000
      vertex -85.334579 -3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -85.767685 -3.994134 15.000000
      vertex -85.334579 -3.994134 0.000000
      vertex -85.767685 -3.994134 0.000000
    endloop
  endfacet
  facet normal 0.108118 0.994138 0.000000
    outer loop
      vertex -86.198265 -3.947306 15.000000
      vertex -85.767685 -3.994134 15.000000
      vertex -85.767685 -3.994134 0.000000
    endloop
  endfacet
  facet normal 0.108118 0.994138 0.000000
    outer loop
      vertex -86.198265 -3.947306 15.000000
      vertex -85.767685 -3.994134 0.000000
      vertex -86.198265 -3.947306 0.000000
    endloop
  endfacet
  facet normal 0.214972 0.976620 0.000000
    outer loop
      vertex -86.621246 -3.854200 15.000000
      vertex -86.198265 -3.947306 15.000000
      vertex -86.198265 -3.947306 0.000000
    endloop
  endfacet
  facet normal 0.214972 0.976620 0.000000
    outer loop
      vertex -86.621246 -3.854200 15.000000
      vertex -86.198265 -3.947306 0.000000
      vertex -86.621246 -3.854200 0.000000
    endloop
  endfacet
  facet normal 0.319302 0.947653 0.000000
    outer loop
      vertex -87.031685 -3.715907 15.000000
      vertex -86.621246 -3.854200 15.000000
      vertex -86.621246 -3.854200 0.000000
    endloop
  endfacet
  facet normal 0.319302 0.947653 0.000000
    outer loop
      vertex -87.031685 -3.715907 15.000000
      vertex -86.621246 -3.854200 0.000000
      vertex -87.031685 -3.715907 0.000000
    endloop
  endfacet
  facet normal 0.419896 0.907572 0.000000
    outer loop
      vertex -87.424759 -3.534048 15.000000
      vertex -87.031685 -3.715907 15.000000
      vertex -87.031685 -3.715907 0.000000
    endloop
  endfacet
  facet normal 0.419896 0.907572 0.000000
    outer loop
      vertex -87.424759 -3.534048 15.000000
      vertex -87.031685 -3.715907 0.000000
      vertex -87.424759 -3.534048 0.000000
    endloop
  endfacet
  facet normal 0.515544 0.856863 0.000000
    outer loop
      vertex -87.795883 -3.310756 15.000000
      vertex -87.424759 -3.534048 15.000000
      vertex -87.424759 -3.534048 0.000000
    endloop
  endfacet
  facet normal 0.515544 0.856863 0.000000
    outer loop
      vertex -87.795883 -3.310756 15.000000
      vertex -87.424759 -3.534048 0.000000
      vertex -87.795883 -3.310756 0.000000
    endloop
  endfacet
  facet normal 0.605185 0.796085 0.000000
    outer loop
      vertex -88.140671 -3.048648 15.000000
      vertex -87.795883 -3.310756 15.000000
      vertex -87.795883 -3.310756 0.000000
    endloop
  endfacet
  facet normal 0.605185 0.796085 0.000000
    outer loop
      vertex -88.140671 -3.048648 15.000000
      vertex -87.795883 -3.310756 0.000000
      vertex -88.140671 -3.048648 0.000000
    endloop
  endfacet
  facet normal 0.687698 0.725997 0.000000
    outer loop
      vertex -88.455109 -2.750798 15.000000
      vertex -88.140671 -3.048648 15.000000
      vertex -88.140671 -3.048648 0.000000
    endloop
  endfacet
  facet normal 0.687698 0.725997 0.000000
    outer loop
      vertex -88.455109 -2.750798 15.000000
      vertex -88.140671 -3.048648 0.000000
      vertex -88.455109 -2.750798 0.000000
    endloop
  endfacet
  facet normal 0.762156 0.647393 0.000000
    outer loop
      vertex -88.735504 -2.420697 15.000000
      vertex -88.455109 -2.750798 15.000000
      vertex -88.455109 -2.750798 0.000000
    endloop
  endfacet
  facet normal 0.762156 0.647393 0.000000
    outer loop
      vertex -88.735504 -2.420697 15.000000
      vertex -88.455109 -2.750798 0.000000
      vertex -88.735504 -2.420697 0.000000
    endloop
  endfacet
  facet normal 0.827688 0.561188 0.000000
    outer loop
      vertex -88.978561 -2.062216 15.000000
      vertex -88.735504 -2.420697 15.000000
      vertex -88.735504 -2.420697 0.000000
    endloop
  endfacet
  facet normal 0.827688 0.561188 0.000000
    outer loop
      vertex -88.978561 -2.062216 15.000000
      vertex -88.735504 -2.420697 0.000000
      vertex -88.978561 -2.062216 0.000000
    endloop
  endfacet
  facet normal 0.883519 0.468395 0.000000
    outer loop
      vertex -89.181427 -1.679556 15.000000
      vertex -88.978561 -2.062216 15.000000
      vertex -88.978561 -2.062216 0.000000
    endloop
  endfacet
  facet normal 0.883519 0.468395 0.000000
    outer loop
      vertex -89.181427 -1.679556 15.000000
      vertex -88.978561 -2.062216 0.000000
      vertex -89.181427 -1.679556 0.000000
    endloop
  endfacet
  facet normal 0.928972 0.370149 0.000000
    outer loop
      vertex -89.341743 -1.277206 15.000000
      vertex -89.181427 -1.679556 15.000000
      vertex -89.181427 -1.679556 0.000000
    endloop
  endfacet
  facet normal 0.928972 0.370149 0.000000
    outer loop
      vertex -89.341743 -1.277206 15.000000
      vertex -89.181427 -1.679556 0.000000
      vertex -89.341743 -1.277206 0.000000
    endloop
  endfacet
  facet normal 0.963547 0.267541 0.000000
    outer loop
      vertex -89.457619 -0.859882 15.000000
      vertex -89.341743 -1.277206 15.000000
      vertex -89.341743 -1.277206 0.000000
    endloop
  endfacet
  facet normal 0.963547 0.267541 0.000000
    outer loop
      vertex -89.457619 -0.859882 15.000000
      vertex -89.341743 -1.277206 0.000000
      vertex -89.457619 -0.859882 0.000000
    endloop
  endfacet
  facet normal 0.986830 0.161762 0.000000
    outer loop
      vertex -89.527679 -0.432476 15.000000
      vertex -89.457619 -0.859882 15.000000
      vertex -89.457619 -0.859882 0.000000
    endloop
  endfacet
  facet normal 0.986830 0.161762 0.000000
    outer loop
      vertex -89.527679 -0.432476 15.000000
      vertex -89.457619 -0.859882 0.000000
      vertex -89.527679 -0.432476 0.000000
    endloop
  endfacet
  facet normal 0.998533 0.054149 0.000000
    outer loop
      vertex -89.551132 -0.000000 15.000000
      vertex -89.527679 -0.432476 15.000000
      vertex -89.527679 -0.432476 0.000000
    endloop
  endfacet
  facet normal 0.998533 0.054149 0.000000
    outer loop
      vertex -89.551132 -0.000000 15.000000
      vertex -89.527679 -0.432476 0.000000
      vertex -89.551132 -0.000000 0.000000
    endloop
  endfacet
  facet normal 0.998533 -0.054149 0.000000
    outer loop
      vertex -89.527664 60.432476 15.000000
      vertex -89.551117 60.000000 15.000000
      vertex -89.551117 60.000000 0.000000
    endloop
  endfacet
  facet normal 0.998533 -0.054149 0.000000
    outer loop
      vertex -89.527664 60.432476 15.000000
      vertex -89.551117 60.000000 0.000000
      vertex -89.527664 60.432476 0.000000
    endloop
  endfacet
  facet normal 0.986830 -0.161762 0.000000
    outer loop
      vertex -89.457603 60.859882 15.000000
      vertex -89.527664 60.432476 15.000000
      vertex -89.527664 60.432476 0.000000
    endloop
  endfacet
  facet normal 0.986830 -0.161762 0.000000
    outer loop
      vertex -89.457603 60.859882 15.000000
      vertex -89.527664 60.432476 0.000000
      vertex -89.457603 60.859882 0.000000
    endloop
  endfacet
  facet normal 0.963547 -0.267541 0.000000
    outer loop
      vertex -89.341728 61.277206 15.000000
      vertex -89.457603 60.859882 15.000000
      vertex -89.457603 60.859882 0.000000
    endloop
  endfacet
  facet normal 0.963547 -0.267541 0.000000
    outer loop
      vertex -89.341728 61.277206 15.000000
      vertex -89.457603 60.859882 0.000000
      vertex -89.341728 61.277206 0.000000
    endloop
  endfacet
  facet normal 0.928979 -0.370133 0.000000
    outer loop
      vertex -89.181419 61.679558 15.000000
      vertex -89.341728 61.277206 15.000000
      vertex -89.341728 61.277206 0.000000
    endloop
  endfacet
  facet normal 0.928979 -0.370133 0.000000
    outer loop
      vertex -89.181419 61.679558 15.000000
      vertex -89.341728 61.277206 0.000000
      vertex -89.181419 61.679558 0.000000
    endloop
  endfacet
  facet normal 0.883510 -0.468412 0.000000
    outer loop
      vertex -88.978546 62.062214 15.000000
      vertex -89.181419 61.679558 15.000000
      vertex -89.181419 61.679558 0.000000
    endloop
  endfacet
  facet normal 0.883510 -0.468412 0.000000
    outer loop
      vertex -88.978546 62.062214 15.000000
      vertex -89.181419 61.679558 0.000000
      vertex -88.978546 62.062214 0.000000
    endloop
  endfacet
  facet normal 0.827689 -0.561187 0.000000
    outer loop
      vertex -88.735489 62.420696 15.000000
      vertex -88.978546 62.062214 15.000000
      vertex -88.978546 62.062214 0.000000
    endloop
  endfacet
  facet normal 0.827689 -0.561187 0.000000
    outer loop
      vertex -88.735489 62.420696 15.000000
      vertex -88.978546 62.062214 0.000000
      vertex -88.735489 62.420696 0.000000
    endloop
  endfacet
  facet normal 0.762160 -0.647389 0.000000
    outer loop
      vertex -88.455093 62.750801 15.000000
      vertex -88.735489 62.420696 15.000000
      vertex -88.735489 62.420696 0.000000
    endloop
  endfacet
  facet normal 0.762160 -0.647389 0.000000
    outer loop
      vertex -88.455093 62.750801 15.000000
      vertex -88.735489 62.420696 0.000000
      vertex -88.455093 62.750801 0.000000
    endloop
  endfacet
  facet normal 0.687690 -0.726004 0.000000
    outer loop
      vertex -88.140656 63.048645 15.000000
      vertex -88.455093 62.750801 15.000000
      vertex -88.455093 62.750801 0.000000
    endloop
  endfacet
  facet normal 0.687690 -0.726004 0.000000
    outer loop
      vertex -88.140656 63.048645 15.000000
      vertex -88.455093 62.750801 0.000000
      vertex -88.140656 63.048645 0.000000
    endloop
  endfacet
  facet normal 0.605182 -0.796087 0.000000
    outer loop
      vertex -87.795860 63.310757 15.000000
      vertex -88.140656 63.048645 15.000000
      vertex -88.140656 63.048645 0.000000
    endloop
  endfacet
  facet normal 0.605182 -0.796087 0.000000
    outer loop
      vertex -87.795860 63.310757 15.000000
      vertex -88.140656 63.048645 0.000000
      vertex -87.795860 63.310757 0.000000
    endloop
  endfacet
  facet normal 0.515561 -0.856853 0.000000
    outer loop
      vertex -87.424751 63.534050 15.000000
      vertex -87.795860 63.310757 15.000000
      vertex -87.795860 63.310757 0.000000
    endloop
  endfacet
  facet normal 0.515561 -0.856853 0.000000
    outer loop
      vertex -87.424751 63.534050 15.000000
      vertex -87.795860 63.310757 0.000000
      vertex -87.424751 63.534050 0.000000
    endloop
  endfacet
  facet normal 0.419880 -0.907580 0.000000
    outer loop
      vertex -87.031670 63.715904 15.000000
      vertex -87.424751 63.534050 15.000000
      vertex -87.424751 63.534050 0.000000
    endloop
  endfacet
  facet normal 0.419880 -0.907580 0.000000
    outer loop
      vertex -87.031670 63.715904 15.000000
      vertex -87.424751 63.534050 0.000000
      vertex -87.031670 63.715904 0.000000
    endloop
  endfacet
  facet normal 0.319312 -0.947649 0.000000
    outer loop
      vertex -86.621231 63.854202 15.000000
      vertex -87.031670 63.715904 15.000000
      vertex -87.031670 63.715904 0.000000
    endloop
  endfacet
  facet normal 0.319312 -0.947649 0.000000
    outer loop
      vertex -86.621231 63.854202 15.000000
      vertex -87.031670 63.715904 0.000000
      vertex -86.621231 63.854202 0.000000
    endloop
  endfacet
  facet normal 0.214959 -0.976623 0.000000
    outer loop
      vertex -86.198242 63.947304 15.000000
      vertex -86.621231 63.854202 15.000000
      vertex -86.621231 63.854202 0.000000
    endloop
  endfacet
  facet normal 0.214959 -0.976623 0.000000
    outer loop
      vertex -86.198242 63.947304 15.000000
      vertex -86.621231 63.854202 0.000000
      vertex -86.198242 63.947304 0.000000
    endloop
  endfacet
  facet normal 0.108123 -0.994138 0.000000
    outer loop
      vertex -85.767670 63.994133 15.000000
      vertex -86.198242 63.947304 15.000000
      vertex -86.198242 63.947304 0.000000
    endloop
  endfacet
  facet normal 0.108123 -0.994138 0.000000
    outer loop
      vertex -85.767670 63.994133 15.000000
      vertex -86.198242 63.947304 0.000000
      vertex -85.767670 63.994133 0.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex -85.334564 63.994133 15.000000
      vertex -85.767670 63.994133 15.000000
      vertex -85.767670 63.994133 0.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex -85.334564 63.994133 15.000000
      vertex -85.767670 63.994133 0.000000
      vertex -85.334564 63.994133 0.000000
    endloop
  endfacet
  facet normal -0.108121 -0.994138 0.000000
    outer loop
      vertex -84.903984 63.947304 15.000000
      vertex -85.334564 63.994133 15.000000
      vertex -85.334564 63.994133 0.000000
    endloop
  endfacet
  facet normal -0.108121 -0.994138 -0.000000
    outer loop
      vertex -84.903984 63.947304 15.000000
      vertex -85.334564 63.994133 0.000000
      vertex -84.903984 63.947304 0.000000
    endloop
  endfacet
  facet normal -0.214962 -0.976622 0.000000
    outer loop
      vertex -84.481003 63.854202 15.000000
      vertex -84.903984 63.947304 15.000000
      vertex -84.903984 63.947304 0.000000
    endloop
  endfacet
  facet normal -0.214962 -0.976622 -0.000000
    outer loop
      vertex -84.481003 63.854202 15.000000
      vertex -84.903984 63.947304 0.000000
      vertex -84.481003 63.854202 0.000000
    endloop
  endfacet
  facet normal -0.319312 -0.947649 0.000000
    outer loop
      vertex -84.070564 63.715904 15.000000
      vertex -84.481003 63.854202 15.000000
      vertex -84.481003 63.854202 0.000000
    endloop
  endfacet
  facet normal -0.319312 -0.947649 -0.000000
    outer loop
      vertex -84.070564 63.715904 15.000000
      vertex -84.481003 63.854202 0.000000
      vertex -84.070564 63.715904 0.000000
    endloop
  endfacet
  facet normal -0.419873 -0.907583 0.000000
    outer loop
      vertex -83.677475 63.534050 15.000000
      vertex -84.070564 63.715904 15.000000
      vertex -84.070564 63.715904 0.000000
    endloop
  endfacet
  facet normal -0.419873 -0.907583 -0.000000
    outer loop
      vertex -83.677475 63.534050 15.000000
      vertex -84.070564 63.715904 0.000000
      vertex -83.677475 63.534050 0.000000
    endloop
  endfacet
  facet normal -0.515561 -0.856853 0.000000
    outer loop
      vertex -83.306366 63.310757 15.000000
      vertex -83.677475 63.534050 15.000000
      vertex -83.677475 63.534050 0.000000
    endloop
  endfacet
  facet normal -0.515561 -0.856853 -0.000000
    outer loop
      vertex -83.306366 63.310757 15.000000
      vertex -83.677475 63.534050 0.000000
      vertex -83.306366 63.310757 0.000000
    endloop
  endfacet
  facet normal -0.605173 -0.796094 0.000000
    outer loop
      vertex -82.961563 63.048645 15.000000
      vertex -83.306366 63.310757 15.000000
      vertex -83.306366 63.310757 0.000000
    endloop
  endfacet
  facet normal -0.605173 -0.796094 -0.000000
    outer loop
      vertex -82.961563 63.048645 15.000000
      vertex -83.306366 63.310757 0.000000
      vertex -82.961563 63.048645 0.000000
    endloop
  endfacet
  facet normal -0.687699 -0.725996 0.000000
    outer loop
      vertex -82.647133 62.750801 15.000000
      vertex -82.961563 63.048645 15.000000
      vertex -82.961563 63.048645 0.000000
    endloop
  endfacet
  facet normal -0.687699 -0.725996 -0.000000
    outer loop
      vertex -82.647133 62.750801 15.000000
      vertex -82.961563 63.048645 0.000000
      vertex -82.647133 62.750801 0.000000
    endloop
  endfacet
  facet normal -0.762169 -0.647379 0.000000
    outer loop
      vertex -82.366745 62.420696 15.000000
      vertex -82.647133 62.750801 15.000000
      vertex -82.647133 62.750801 0.000000
    endloop
  endfacet
  facet normal -0.762169 -0.647379 -0.000000
    outer loop
      vertex -82.366745 62.420696 15.000000
      vertex -82.647133 62.750801 0.000000
      vertex -82.366745 62.420696 0.000000
    endloop
  endfacet
  facet normal -0.827689 -0.561187 0.000000
    outer loop
      vertex -82.123688 62.062214 15.000000
      vertex -82.366745 62.420696 15.000000
      vertex -82.366745 62.420696 0.000000
    endloop
  endfacet
  facet normal -0.827689 -0.561187 -0.000000
    outer loop
      vertex -82.123688 62.062214 15.000000
      vertex -82.366745 62.420696 0.000000
      vertex -82.123688 62.062214 0.000000
    endloop
  endfacet
  facet normal -0.883510 -0.468412 0.000000
    outer loop
      vertex -81.920815 61.679558 15.000000
      vertex -82.123688 62.062214 15.000000
      vertex -82.123688 62.062214 0.000000
    endloop
  endfacet
  facet normal -0.883510 -0.468412 -0.000000
    outer loop
      vertex -81.920815 61.679558 15.000000
      vertex -82.123688 62.062214 0.000000
      vertex -81.920815 61.679558 0.000000
    endloop
  endfacet
  facet normal -0.928979 -0.370133 0.000000
    outer loop
      vertex -81.760506 61.277206 15.000000
      vertex -81.920815 61.679558 15.000000
      vertex -81.920815 61.679558 0.000000
    endloop
  endfacet
  facet normal -0.928979 -0.370133 -0.000000
    outer loop
      vertex -81.760506 61.277206 15.000000
      vertex -81.920815 61.679558 0.000000
      vertex -81.760506 61.277206 0.000000
    endloop
  endfacet
  facet normal -0.963547 -0.267541 0.000000
    outer loop
      vertex -81.644630 60.859882 15.000000
      vertex -81.760506 61.277206 15.000000
      vertex -81.760506 61.277206 0.000000
    endloop
  endfacet
  facet normal -0.963547 -0.267541 -0.000000
    outer loop
      vertex -81.644630 60.859882 15.000000
      vertex -81.760506 61.277206 0.000000
      vertex -81.644630 60.859882 0.000000
    endloop
  endfacet
  facet normal -0.986830 -0.161762 0.000000
    outer loop
      vertex -81.574570 60.432476 15.000000
      vertex -81.644630 60.859882 15.000000
      vertex -81.644630 60.859882 0.000000
    endloop
  endfacet
  facet normal -0.986830 -0.161762 -0.000000
    outer loop
      vertex -81.574570 60.432476 15.000000
      vertex -81.644630 60.859882 0.000000
      vertex -81.574570 60.432476 0.000000
    endloop
  endfacet
  facet normal -0.998532 -0.054167 0.000000
    outer loop
      vertex -81.551109 60.000000 15.000000
      vertex -81.574570 60.432476 15.000000
      vertex -81.574570 60.432476 0.000000
    endloop
  endfacet
  facet normal -0.998532 -0.054167 -0.000000
    outer loop
      vertex -81.551109 60.000000 15.000000
      vertex -81.574570 60.432476 0.000000
      vertex -81.551109 60.000000 0.000000
    endloop
  endfacet
  facet normal -0.998532 0.054167 0.000000
    outer loop
      vertex -81.574570 59.567524 15.000000
      vertex -81.551109 60.000000 15.000000
      vertex -81.551109 60.000000 0.000000
    endloop
  endfacet
  facet normal -0.998532 0.054167 0.000000
    outer loop
      vertex -81.574570 59.567524 15.000000
      vertex -81.551109 60.000000 0.000000
      vertex -81.574570 59.567524 0.000000
    endloop
  endfacet
  facet normal -0.986830 0.161763 0.000000
    outer loop
      vertex -81.644630 59.140121 15.000000
      vertex -81.574570 59.567524 15.000000
      vertex -81.574570 59.567524 0.000000
    endloop
  endfacet
  facet normal -0.986830 0.161763 0.000000
    outer loop
      vertex -81.644630 59.140121 15.000000
      vertex -81.574570 59.567524 0.000000
      vertex -81.644630 59.140121 0.000000
    endloop
  endfacet
  facet normal -0.963547 0.267538 0.000000
    outer loop
      vertex -81.760506 58.722794 15.000000
      vertex -81.644630 59.140121 15.000000
      vertex -81.644630 59.140121 0.000000
    endloop
  endfacet
  facet normal -0.963547 0.267538 0.000000
    outer loop
      vertex -81.760506 58.722794 15.000000
      vertex -81.644630 59.140121 0.000000
      vertex -81.760506 58.722794 0.000000
    endloop
  endfacet
  facet normal -0.928979 0.370133 0.000000
    outer loop
      vertex -81.920815 58.320442 15.000000
      vertex -81.760506 58.722794 15.000000
      vertex -81.760506 58.722794 0.000000
    endloop
  endfacet
  facet normal -0.928979 0.370133 0.000000
    outer loop
      vertex -81.920815 58.320442 15.000000
      vertex -81.760506 58.722794 0.000000
      vertex -81.920815 58.320442 0.000000
    endloop
  endfacet
  facet normal -0.883510 0.468412 0.000000
    outer loop
      vertex -82.123688 57.937786 15.000000
      vertex -81.920815 58.320442 15.000000
      vertex -81.920815 58.320442 0.000000
    endloop
  endfacet
  facet normal -0.883510 0.468412 0.000000
    outer loop
      vertex -82.123688 57.937786 15.000000
      vertex -81.920815 58.320442 0.000000
      vertex -82.123688 57.937786 0.000000
    endloop
  endfacet
  facet normal -0.827692 0.561183 0.000000
    outer loop
      vertex -82.366745 57.579300 15.000000
      vertex -82.123688 57.937786 15.000000
      vertex -82.123688 57.937786 0.000000
    endloop
  endfacet
  facet normal -0.827692 0.561183 0.000000
    outer loop
      vertex -82.366745 57.579300 15.000000
      vertex -82.123688 57.937786 0.000000
      vertex -82.366745 57.579300 0.000000
    endloop
  endfacet
  facet normal -0.762161 0.647387 0.000000
    outer loop
      vertex -82.647133 57.249203 15.000000
      vertex -82.366745 57.579300 15.000000
      vertex -82.366745 57.579300 0.000000
    endloop
  endfacet
  facet normal -0.762161 0.647387 0.000000
    outer loop
      vertex -82.647133 57.249203 15.000000
      vertex -82.366745 57.579300 0.000000
      vertex -82.647133 57.249203 0.000000
    endloop
  endfacet
  facet normal -0.687708 0.725987 0.000000
    outer loop
      vertex -82.961563 56.951351 15.000000
      vertex -82.647133 57.249203 15.000000
      vertex -82.647133 57.249203 0.000000
    endloop
  endfacet
  facet normal -0.687708 0.725987 0.000000
    outer loop
      vertex -82.961563 56.951351 15.000000
      vertex -82.647133 57.249203 0.000000
      vertex -82.961563 56.951351 0.000000
    endloop
  endfacet
  facet normal -0.605168 0.796098 0.000000
    outer loop
      vertex -83.306366 56.689243 15.000000
      vertex -82.961563 56.951351 15.000000
      vertex -82.961563 56.951351 0.000000
    endloop
  endfacet
  facet normal -0.605168 0.796098 0.000000
    outer loop
      vertex -83.306366 56.689243 15.000000
      vertex -82.961563 56.951351 0.000000
      vertex -83.306366 56.689243 0.000000
    endloop
  endfacet
  facet normal -0.515555 0.856857 0.000000
    outer loop
      vertex -83.677475 56.465954 15.000000
      vertex -83.306366 56.689243 15.000000
      vertex -83.306366 56.689243 0.000000
    endloop
  endfacet
  facet normal -0.515555 0.856857 0.000000
    outer loop
      vertex -83.677475 56.465954 15.000000
      vertex -83.306366 56.689243 0.000000
      vertex -83.677475 56.465954 0.000000
    endloop
  endfacet
  facet normal -0.419888 0.907576 0.000000
    outer loop
      vertex -84.070564 56.284092 15.000000
      vertex -83.677475 56.465954 15.000000
      vertex -83.677475 56.465954 0.000000
    endloop
  endfacet
  facet normal -0.419888 0.907576 0.000000
    outer loop
      vertex -84.070564 56.284092 15.000000
      vertex -83.677475 56.465954 0.000000
      vertex -84.070564 56.284092 0.000000
    endloop
  endfacet
  facet normal -0.319304 0.947652 0.000000
    outer loop
      vertex -84.481003 56.145798 15.000000
      vertex -84.070564 56.284092 15.000000
      vertex -84.070564 56.284092 0.000000
    endloop
  endfacet
  facet normal -0.319304 0.947652 0.000000
    outer loop
      vertex -84.481003 56.145798 15.000000
      vertex -84.070564 56.284092 0.000000
      vertex -84.481003 56.145798 0.000000
    endloop
  endfacet
  facet normal -0.214971 0.976620 0.000000
    outer loop
      vertex -84.903984 56.052692 15.000000
      vertex -84.481003 56.145798 15.000000
      vertex -84.481003 56.145798 0.000000
    endloop
  endfacet
  facet normal -0.214971 0.976620 0.000000
    outer loop
      vertex -84.903984 56.052692 15.000000
      vertex -84.481003 56.145798 0.000000
      vertex -84.903984 56.052692 0.000000
    endloop
  endfacet
  facet normal -0.108112 0.994139 0.000000
    outer loop
      vertex -85.334564 56.005867 15.000000
      vertex -84.903984 56.052692 15.000000
      vertex -84.903984 56.052692 0.000000
    endloop
  endfacet
  facet normal -0.108112 0.994139 0.000000
    outer loop
      vertex -85.334564 56.005867 15.000000
      vertex -84.903984 56.052692 0.000000
      vertex -85.334564 56.005867 0.000000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -85.767670 56.005867 15.000000
      vertex -85.334564 56.005867 15.000000
      vertex -85.334564 56.005867 0.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -85.767670 56.005867 15.000000
      vertex -85.334564 56.005867 0.000000
      vertex -85.767670 56.005867 0.000000
    endloop
  endfacet
  facet normal 0.108114 0.994138 0.000000
    outer loop
      vertex -86.198242 56.052692 15.000000
      vertex -85.767670 56.005867 15.000000
      vertex -85.767670 56.005867 0.000000
    endloop
  endfacet
  facet normal 0.108114 0.994138 0.000000
    outer loop
      vertex -86.198242 56.052692 15.000000
      vertex -85.767670 56.005867 0.000000
      vertex -86.198242 56.052692 0.000000
    endloop
  endfacet
  facet normal 0.214967 0.976621 0.000000
    outer loop
      vertex -86.621231 56.145798 15.000000
      vertex -86.198242 56.052692 15.000000
      vertex -86.198242 56.052692 0.000000
    endloop
  endfacet
  facet normal 0.214967 0.976621 0.000000
    outer loop
      vertex -86.621231 56.145798 15.000000
      vertex -86.198242 56.052692 0.000000
      vertex -86.621231 56.145798 0.000000
    endloop
  endfacet
  facet normal 0.319304 0.947652 0.000000
    outer loop
      vertex -87.031670 56.284092 15.000000
      vertex -86.621231 56.145798 15.000000
      vertex -86.621231 56.145798 0.000000
    endloop
  endfacet
  facet normal 0.319304 0.947652 0.000000
    outer loop
      vertex -87.031670 56.284092 15.000000
      vertex -86.621231 56.145798 0.000000
      vertex -87.031670 56.284092 0.000000
    endloop
  endfacet
  facet normal 0.419895 0.907573 0.000000
    outer loop
      vertex -87.424751 56.465954 15.000000
      vertex -87.031670 56.284092 15.000000
      vertex -87.031670 56.284092 0.000000
    endloop
  endfacet
  facet normal 0.419895 0.907573 0.000000
    outer loop
      vertex -87.424751 56.465954 15.000000
      vertex -87.031670 56.284092 0.000000
      vertex -87.424751 56.465954 0.000000
    endloop
  endfacet
  facet normal 0.515555 0.856857 0.000000
    outer loop
      vertex -87.795860 56.689243 15.000000
      vertex -87.424751 56.465954 15.000000
      vertex -87.424751 56.465954 0.000000
    endloop
  endfacet
  facet normal 0.515555 0.856857 0.000000
    outer loop
      vertex -87.795860 56.689243 15.000000
      vertex -87.424751 56.465954 0.000000
      vertex -87.795860 56.689243 0.000000
    endloop
  endfacet
  facet normal 0.605176 0.796092 0.000000
    outer loop
      vertex -88.140656 56.951351 15.000000
      vertex -87.795860 56.689243 15.000000
      vertex -87.795860 56.689243 0.000000
    endloop
  endfacet
  facet normal 0.605176 0.796092 0.000000
    outer loop
      vertex -88.140656 56.951351 15.000000
      vertex -87.795860 56.689243 0.000000
      vertex -88.140656 56.951351 0.000000
    endloop
  endfacet
  facet normal 0.687700 0.725995 0.000000
    outer loop
      vertex -88.455093 57.249203 15.000000
      vertex -88.140656 56.951351 15.000000
      vertex -88.140656 56.951351 0.000000
    endloop
  endfacet
  facet normal 0.687700 0.725995 0.000000
    outer loop
      vertex -88.455093 57.249203 15.000000
      vertex -88.140656 56.951351 0.000000
      vertex -88.455093 57.249203 0.000000
    endloop
  endfacet
  facet normal 0.762152 0.647398 0.000000
    outer loop
      vertex -88.735489 57.579300 15.000000
      vertex -88.455093 57.249203 15.000000
      vertex -88.455093 57.249203 0.000000
    endloop
  endfacet
  facet normal 0.762152 0.647398 0.000000
    outer loop
      vertex -88.735489 57.579300 15.000000
      vertex -88.455093 57.249203 0.000000
      vertex -88.735489 57.579300 0.000000
    endloop
  endfacet
  facet normal 0.827692 0.561183 0.000000
    outer loop
      vertex -88.978546 57.937786 15.000000
      vertex -88.735489 57.579300 15.000000
      vertex -88.735489 57.579300 0.000000
    endloop
  endfacet
  facet normal 0.827692 0.561183 0.000000
    outer loop
      vertex -88.978546 57.937786 15.000000
      vertex -88.735489 57.579300 0.000000
      vertex -88.978546 57.937786 0.000000
    endloop
  endfacet
  facet normal 0.883510 0.468412 0.000000
    outer loop
      vertex -89.181419 58.320442 15.000000
      vertex -88.978546 57.937786 15.000000
      vertex -88.978546 57.937786 0.000000
    endloop
  endfacet
  facet normal 0.883510 0.468412 0.000000
    outer loop
      vertex -89.181419 58.320442 15.000000
      vertex -88.978546 57.937786 0.000000
      vertex -89.181419 58.320442 0.000000
    endloop
  endfacet
  facet normal 0.928979 0.370133 0.000000
    outer loop
      vertex -89.341728 58.722794 15.000000
      vertex -89.181419 58.320442 15.000000
      vertex -89.181419 58.320442 0.000000
    endloop
  endfacet
  facet normal 0.928979 0.370133 0.000000
    outer loop
      vertex -89.341728 58.722794 15.000000
      vertex -89.181419 58.320442 0.000000
      vertex -89.341728 58.722794 0.000000
    endloop
  endfacet
  facet normal 0.963547 0.267538 0.000000
    outer loop
      vertex -89.457603 59.140121 15.000000
      vertex -89.341728 58.722794 15.000000
      vertex -89.341728 58.722794 0.000000
    endloop
  endfacet
  facet normal 0.963547 0.267538 0.000000
    outer loop
      vertex -89.457603 59.140121 15.000000
      vertex -89.341728 58.722794 0.000000
      vertex -89.457603 59.140121 0.000000
    endloop
  endfacet
  facet normal 0.986830 0.161763 0.000000
    outer loop
      vertex -89.527664 59.567524 15.000000
      vertex -89.457603 59.140121 15.000000
      vertex -89.457603 59.140121 0.000000
    endloop
  endfacet
  facet normal 0.986830 0.161763 0.000000
    outer loop
      vertex -89.527664 59.567524 15.000000
      vertex -89.457603 59.140121 0.000000
      vertex -89.527664 59.567524 0.000000
    endloop
  endfacet
  facet normal 0.998533 0.054149 0.000000
    outer loop
      vertex -89.551117 60.000000 15.000000
      vertex -89.527664 59.567524 15.000000
      vertex -89.527664 59.567524 0.000000
    endloop
  endfacet
  facet normal 0.998533 0.054149 0.000000
    outer loop
      vertex -89.551117 60.000000 15.000000
      vertex -89.527664 59.567524 0.000000
      vertex -89.551117 60.000000 0.000000
    endloop
  endfacet
  facet normal 0.998533 -0.054138 0.000000
    outer loop
      vertex -3.527684 0.432476 15.000000
      vertex -3.551132 -0.000000 15.000000
      vertex -3.551132 -0.000000 0.000000
    endloop
  endfacet
  facet normal 0.998533 -0.054138 0.000000
    outer loop
      vertex -3.527684 0.432476 15.000000
      vertex -3.551132 -0.000000 0.000000
      vertex -3.527684 0.432476 0.000000
    endloop
  endfacet
  facet normal 0.986826 -0.161782 0.000000
    outer loop
      vertex -3.457615 0.859882 15.000000
      vertex -3.527684 0.432476 15.000000
      vertex -3.527684 0.432476 0.000000
    endloop
  endfacet
  facet normal 0.986826 -0.161782 0.000000
    outer loop
      vertex -3.457615 0.859882 15.000000
      vertex -3.527684 0.432476 0.000000
      vertex -3.457615 0.859882 0.000000
    endloop
  endfacet
  facet normal 0.963550 -0.267528 0.000000
    outer loop
      vertex -3.341745 1.277206 15.000000
      vertex -3.457615 0.859882 15.000000
      vertex -3.457615 0.859882 0.000000
    endloop
  endfacet
  facet normal 0.963550 -0.267528 0.000000
    outer loop
      vertex -3.341745 1.277206 15.000000
      vertex -3.457615 0.859882 0.000000
      vertex -3.341745 1.277206 0.000000
    endloop
  endfacet
  facet normal 0.928977 -0.370138 0.000000
    outer loop
      vertex -3.181434 1.679556 15.000000
      vertex -3.341745 1.277206 15.000000
      vertex -3.341745 1.277206 0.000000
    endloop
  endfacet
  facet normal 0.928977 -0.370138 0.000000
    outer loop
      vertex -3.181434 1.679556 15.000000
      vertex -3.341745 1.277206 0.000000
      vertex -3.181434 1.679556 0.000000
    endloop
  endfacet
  facet normal 0.883512 -0.468408 0.000000
    outer loop
      vertex -2.978561 2.062216 15.000000
      vertex -3.181434 1.679556 15.000000
      vertex -3.181434 1.679556 0.000000
    endloop
  endfacet
  facet normal 0.883512 -0.468408 0.000000
    outer loop
      vertex -2.978561 2.062216 15.000000
      vertex -3.181434 1.679556 0.000000
      vertex -2.978561 2.062216 0.000000
    endloop
  endfacet
  facet normal 0.827689 -0.561187 0.000000
    outer loop
      vertex -2.735505 2.420697 15.000000
      vertex -2.978561 2.062216 15.000000
      vertex -2.978561 2.062216 0.000000
    endloop
  endfacet
  facet normal 0.827689 -0.561187 0.000000
    outer loop
      vertex -2.735505 2.420697 15.000000
      vertex -2.978561 2.062216 0.000000
      vertex -2.735505 2.420697 0.000000
    endloop
  endfacet
  facet normal 0.762162 -0.647386 0.000000
    outer loop
      vertex -2.455114 2.750798 15.000000
      vertex -2.735505 2.420697 15.000000
      vertex -2.735505 2.420697 0.000000
    endloop
  endfacet
  facet normal 0.762162 -0.647386 0.000000
    outer loop
      vertex -2.455114 2.750798 15.000000
      vertex -2.735505 2.420697 0.000000
      vertex -2.455114 2.750798 0.000000
    endloop
  endfacet
  facet normal 0.687699 -0.725996 0.000000
    outer loop
      vertex -2.140677 3.048648 15.000000
      vertex -2.455114 2.750798 15.000000
      vertex -2.455114 2.750798 0.000000
    endloop
  endfacet
  facet normal 0.687699 -0.725996 0.000000
    outer loop
      vertex -2.140677 3.048648 15.000000
      vertex -2.455114 2.750798 0.000000
      vertex -2.140677 3.048648 0.000000
    endloop
  endfacet
  facet normal 0.605174 -0.796093 0.000000
    outer loop
      vertex -1.795881 3.310756 15.000000
      vertex -2.140677 3.048648 15.000000
      vertex -2.140677 3.048648 0.000000
    endloop
  endfacet
  facet normal 0.605174 -0.796093 0.000000
    outer loop
      vertex -1.795881 3.310756 15.000000
      vertex -2.140677 3.048648 0.000000
      vertex -1.795881 3.310756 0.000000
    endloop
  endfacet
  facet normal 0.515554 -0.856857 0.000000
    outer loop
      vertex -1.424766 3.534048 15.000000
      vertex -1.795881 3.310756 15.000000
      vertex -1.795881 3.310756 0.000000
    endloop
  endfacet
  facet normal 0.515554 -0.856857 0.000000
    outer loop
      vertex -1.424766 3.534048 15.000000
      vertex -1.795881 3.310756 0.000000
      vertex -1.424766 3.534048 0.000000
    endloop
  endfacet
  facet normal 0.419890 -0.907575 0.000000
    outer loop
      vertex -1.031685 3.715907 15.000000
      vertex -1.424766 3.534048 15.000000
      vertex -1.424766 3.534048 0.000000
    endloop
  endfacet
  facet normal 0.419890 -0.907575 0.000000
    outer loop
      vertex -1.031685 3.715907 15.000000
      vertex -1.424766 3.534048 0.000000
      vertex -1.031685 3.715907 0.000000
    endloop
  endfacet
  facet normal 0.319301 -0.947653 0.000000
    outer loop
      vertex -0.621246 3.854200 15.000000
      vertex -1.031685 3.715907 15.000000
      vertex -1.031685 3.715907 0.000000
    endloop
  endfacet
  facet normal 0.319301 -0.947653 0.000000
    outer loop
      vertex -0.621246 3.854200 15.000000
      vertex -1.031685 3.715907 0.000000
      vertex -0.621246 3.854200 0.000000
    endloop
  endfacet
  facet normal 0.214970 -0.976621 0.000000
    outer loop
      vertex -0.198260 3.947306 15.000000
      vertex -0.621246 3.854200 15.000000
      vertex -0.621246 3.854200 0.000000
    endloop
  endfacet
  facet normal 0.214970 -0.976621 0.000000
    outer loop
      vertex -0.198260 3.947306 15.000000
      vertex -0.621246 3.854200 0.000000
      vertex -0.198260 3.947306 0.000000
    endloop
  endfacet
  facet normal 0.108120 -0.994138 0.000000
    outer loop
      vertex 0.232312 3.994134 15.000000
      vertex -0.198260 3.947306 15.000000
      vertex -0.198260 3.947306 0.000000
    endloop
  endfacet
  facet normal 0.108120 -0.994138 0.000000
    outer loop
      vertex 0.232312 3.994134 15.000000
      vertex -0.198260 3.947306 0.000000
      vertex 0.232312 3.994134 0.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 0.000000
    outer loop
      vertex 0.665423 3.994134 15.000000
      vertex 0.232312 3.994134 15.000000
      vertex 0.232312 3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 -0.000000
    outer loop
      vertex 0.665423 3.994134 15.000000
      vertex 0.232312 3.994134 0.000000
      vertex 0.665423 3.994134 0.000000
    endloop
  endfacet
  facet normal -0.108120 -0.994138 0.000000
    outer loop
      vertex 1.095996 3.947306 15.000000
      vertex 0.665423 3.994134 15.000000
      vertex 0.665423 3.994134 0.000000
    endloop
  endfacet
  facet normal -0.108120 -0.994138 -0.000000
    outer loop
      vertex 1.095996 3.947306 15.000000
      vertex 0.665423 3.994134 0.000000
      vertex 1.095996 3.947306 0.000000
    endloop
  endfacet
  facet normal -0.214970 -0.976621 0.000000
    outer loop
      vertex 1.518981 3.854200 15.000000
      vertex 1.095996 3.947306 15.000000
      vertex 1.095996 3.947306 0.000000
    endloop
  endfacet
  facet normal -0.214970 -0.976621 -0.000000
    outer loop
      vertex 1.518981 3.854200 15.000000
      vertex 1.095996 3.947306 0.000000
      vertex 1.518981 3.854200 0.000000
    endloop
  endfacet
  facet normal -0.319301 -0.947653 0.000000
    outer loop
      vertex 1.929420 3.715907 15.000000
      vertex 1.518981 3.854200 15.000000
      vertex 1.518981 3.854200 0.000000
    endloop
  endfacet
  facet normal -0.319301 -0.947653 -0.000000
    outer loop
      vertex 1.929420 3.715907 15.000000
      vertex 1.518981 3.854200 0.000000
      vertex 1.929420 3.715907 0.000000
    endloop
  endfacet
  facet normal -0.419890 -0.907575 0.000000
    outer loop
      vertex 2.322501 3.534048 15.000000
      vertex 1.929420 3.715907 15.000000
      vertex 1.929420 3.715907 0.000000
    endloop
  endfacet
  facet normal -0.419890 -0.907575 -0.000000
    outer loop
      vertex 2.322501 3.534048 15.000000
      vertex 1.929420 3.715907 0.000000
      vertex 2.322501 3.534048 0.000000
    endloop
  endfacet
  facet normal -0.515553 -0.856857 0.000000
    outer loop
      vertex 2.693616 3.310756 15.000000
      vertex 2.322501 3.534048 15.000000
      vertex 2.322501 3.534048 0.000000
    endloop
  endfacet
  facet normal -0.515553 -0.856857 -0.000000
    outer loop
      vertex 2.693616 3.310756 15.000000
      vertex 2.322501 3.534048 0.000000
      vertex 2.693616 3.310756 0.000000
    endloop
  endfacet
  facet normal -0.605175 -0.796093 0.000000
    outer loop
      vertex 3.038413 3.048648 15.000000
      vertex 2.693616 3.310756 15.000000
      vertex 2.693616 3.310756 0.000000
    endloop
  endfacet
  facet normal -0.605175 -0.796093 -0.000000
    outer loop
      vertex 3.038413 3.048648 15.000000
      vertex 2.693616 3.310756 0.000000
      vertex 3.038413 3.048648 0.000000
    endloop
  endfacet
  facet normal -0.687699 -0.725996 0.000000
    outer loop
      vertex 3.352849 2.750798 15.000000
      vertex 3.038413 3.048648 15.000000
      vertex 3.038413 3.048648 0.000000
    endloop
  endfacet
  facet normal -0.687699 -0.725996 -0.000000
    outer loop
      vertex 3.352849 2.750798 15.000000
      vertex 3.038413 3.048648 0.000000
      vertex 3.352849 2.750798 0.000000
    endloop
  endfacet
  facet normal -0.762162 -0.647386 0.000000
    outer loop
      vertex 3.633240 2.420697 15.000000
      vertex 3.352849 2.750798 15.000000
      vertex 3.352849 2.750798 0.000000
    endloop
  endfacet
  facet normal -0.762162 -0.647386 -0.000000
    outer loop
      vertex 3.633240 2.420697 15.000000
      vertex 3.352849 2.750798 0.000000
      vertex 3.633240 2.420697 0.000000
    endloop
  endfacet
  facet normal -0.827689 -0.561187 0.000000
    outer loop
      vertex 3.876296 2.062216 15.000000
      vertex 3.633240 2.420697 15.000000
      vertex 3.633240 2.420697 0.000000
    endloop
  endfacet
  facet normal -0.827689 -0.561187 -0.000000
    outer loop
      vertex 3.876296 2.062216 15.000000
      vertex 3.633240 2.420697 0.000000
      vertex 3.876296 2.062216 0.000000
    endloop
  endfacet
  facet normal -0.883512 -0.468408 0.000000
    outer loop
      vertex 4.079169 1.679556 15.000000
      vertex 3.876296 2.062216 15.000000
      vertex 3.876296 2.062216 0.000000
    endloop
  endfacet
  facet normal -0.883512 -0.468408 -0.000000
    outer loop
      vertex 4.079169 1.679556 15.000000
      vertex 3.876296 2.062216 0.000000
      vertex 4.079169 1.679556 0.000000
    endloop
  endfacet
  facet normal -0.928977 -0.370138 0.000000
    outer loop
      vertex 4.239480 1.277206 15.000000
      vertex 4.079169 1.679556 15.000000
      vertex 4.079169 1.679556 0.000000
    endloop
  endfacet
  facet normal -0.928977 -0.370138 -0.000000
    outer loop
      vertex 4.239480 1.277206 15.000000
      vertex 4.079169 1.679556 0.000000
      vertex 4.239480 1.277206 0.000000
    endloop
  endfacet
  facet normal -0.963550 -0.267527 0.000000
    outer loop
      vertex 4.355350 0.859882 15.000000
      vertex 4.239480 1.277206 15.000000
      vertex 4.239480 1.277206 0.000000
    endloop
  endfacet
  facet normal -0.963550 -0.267527 -0.000000
    outer loop
      vertex 4.355350 0.859882 15.000000
      vertex 4.239480 1.277206 0.000000
      vertex 4.355350 0.859882 0.000000
    endloop
  endfacet
  facet normal -0.986826 -0.161782 0.000000
    outer loop
      vertex 4.425419 0.432476 15.000000
      vertex 4.355350 0.859882 15.000000
      vertex 4.355350 0.859882 0.000000
    endloop
  endfacet
  facet normal -0.986826 -0.161782 -0.000000
    outer loop
      vertex 4.425419 0.432476 15.000000
      vertex 4.355350 0.859882 0.000000
      vertex 4.425419 0.432476 0.000000
    endloop
  endfacet
  facet normal -0.998533 -0.054138 0.000000
    outer loop
      vertex 4.448867 -0.000000 15.000000
      vertex 4.425419 0.432476 15.000000
      vertex 4.425419 0.432476 0.000000
    endloop
  endfacet
  facet normal -0.998533 -0.054138 -0.000000
    outer loop
      vertex 4.448867 -0.000000 15.000000
      vertex 4.425419 0.432476 0.000000
      vertex 4.448867 -0.000000 0.000000
    endloop
  endfacet
  facet normal -0.998533 0.054138 0.000000
    outer loop
      vertex 4.425419 -0.432476 15.000000
      vertex 4.448867 -0.000000 15.000000
      vertex 4.448867 -0.000000 0.000000
    endloop
  endfacet
  facet normal -0.998533 0.054138 0.000000
    outer loop
      vertex 4.425419 -0.432476 15.000000
      vertex 4.448867 -0.000000 0.000000
      vertex 4.425419 -0.432476 0.000000
    endloop
  endfacet
  facet normal -0.986826 0.161782 0.000000
    outer loop
      vertex 4.355350 -0.859882 15.000000
      vertex 4.425419 -0.432476 15.000000
      vertex 4.425419 -0.432476 0.000000
    endloop
  endfacet
  facet normal -0.986826 0.161782 0.000000
    outer loop
      vertex 4.355350 -0.859882 15.000000
      vertex 4.425419 -0.432476 0.000000
      vertex 4.355350 -0.859882 0.000000
    endloop
  endfacet
  facet normal -0.963550 0.267527 0.000000
    outer loop
      vertex 4.239480 -1.277206 15.000000
      vertex 4.355350 -0.859882 15.000000
      vertex 4.355350 -0.859882 0.000000
    endloop
  endfacet
  facet normal -0.963550 0.267527 0.000000
    outer loop
      vertex 4.239480 -1.277206 15.000000
      vertex 4.355350 -0.859882 0.000000
      vertex 4.239480 -1.277206 0.000000
    endloop
  endfacet
  facet normal -0.928977 0.370138 0.000000
    outer loop
      vertex 4.079169 -1.679556 15.000000
      vertex 4.239480 -1.277206 15.000000
      vertex 4.239480 -1.277206 0.000000
    endloop
  endfacet
  facet normal -0.928977 0.370138 0.000000
    outer loop
      vertex 4.079169 -1.679556 15.000000
      vertex 4.239480 -1.277206 0.000000
      vertex 4.079169 -1.679556 0.000000
    endloop
  endfacet
  facet normal -0.883512 0.468408 0.000000
    outer loop
      vertex 3.876296 -2.062216 15.000000
      vertex 4.079169 -1.679556 15.000000
      vertex 4.079169 -1.679556 0.000000
    endloop
  endfacet
  facet normal -0.883512 0.468408 0.000000
    outer loop
      vertex 3.876296 -2.062216 15.000000
      vertex 4.079169 -1.679556 0.000000
      vertex 3.876296 -2.062216 0.000000
    endloop
  endfacet
  facet normal -0.827689 0.561187 0.000000
    outer loop
      vertex 3.633240 -2.420697 15.000000
      vertex 3.876296 -2.062216 15.000000
      vertex 3.876296 -2.062216 0.000000
    endloop
  endfacet
  facet normal -0.827689 0.561187 0.000000
    outer loop
      vertex 3.633240 -2.420697 15.000000
      vertex 3.876296 -2.062216 0.000000
      vertex 3.633240 -2.420697 0.000000
    endloop
  endfacet
  facet normal -0.762162 0.647386 0.000000
    outer loop
      vertex 3.352849 -2.750798 15.000000
      vertex 3.633240 -2.420697 15.000000
      vertex 3.633240 -2.420697 0.000000
    endloop
  endfacet
  facet normal -0.762162 0.647386 0.000000
    outer loop
      vertex 3.352849 -2.750798 15.000000
      vertex 3.633240 -2.420697 0.000000
      vertex 3.352849 -2.750798 0.000000
    endloop
  endfacet
  facet normal -0.687699 0.725996 0.000000
    outer loop
      vertex 3.038413 -3.048648 15.000000
      vertex 3.352849 -2.750798 15.000000
      vertex 3.352849 -2.750798 0.000000
    endloop
  endfacet
  facet normal -0.687699 0.725996 0.000000
    outer loop
      vertex 3.038413 -3.048648 15.000000
      vertex 3.352849 -2.750798 0.000000
      vertex 3.038413 -3.048648 0.000000
    endloop
  endfacet
  facet normal -0.605175 0.796093 0.000000
    outer loop
      vertex 2.693616 -3.310756 15.000000
      vertex 3.038413 -3.048648 15.000000
      vertex 3.038413 -3.048648 0.000000
    endloop
  endfacet
  facet normal -0.605175 0.796093 0.000000
    outer loop
      vertex 2.693616 -3.310756 15.000000
      vertex 3.038413 -3.048648 0.000000
      vertex 2.693616 -3.310756 0.000000
    endloop
  endfacet
  facet normal -0.515553 0.856857 0.000000
    outer loop
      vertex 2.322501 -3.534048 15.000000
      vertex 2.693616 -3.310756 15.000000
      vertex 2.693616 -3.310756 0.000000
    endloop
  endfacet
  facet normal -0.515553 0.856857 0.000000
    outer loop
      vertex 2.322501 -3.534048 15.000000
      vertex 2.693616 -3.310756 0.000000
      vertex 2.322501 -3.534048 0.000000
    endloop
  endfacet
  facet normal -0.419890 0.907575 0.000000
    outer loop
      vertex 1.929420 -3.715907 15.000000
      vertex 2.322501 -3.534048 15.000000
      vertex 2.322501 -3.534048 0.000000
    endloop
  endfacet
  facet normal -0.419890 0.907575 0.000000
    outer loop
      vertex 1.929420 -3.715907 15.000000
      vertex 2.322501 -3.534048 0.000000
      vertex 1.929420 -3.715907 0.000000
    endloop
  endfacet
  facet normal -0.319301 0.947653 0.000000
    outer loop
      vertex 1.518981 -3.854200 15.000000
      vertex 1.929420 -3.715907 15.000000
      vertex 1.929420 -3.715907 0.000000
    endloop
  endfacet
  facet normal -0.319301 0.947653 0.000000
    outer loop
      vertex 1.518981 -3.854200 15.000000
      vertex 1.929420 -3.715907 0.000000
      vertex 1.518981 -3.854200 0.000000
    endloop
  endfacet
  facet normal -0.214970 0.976621 0.000000
    outer loop
      vertex 1.095996 -3.947306 15.000000
      vertex 1.518981 -3.854200 15.000000
      vertex 1.518981 -3.854200 0.000000
    endloop
  endfacet
  facet normal -0.214970 0.976621 0.000000
    outer loop
      vertex 1.095996 -3.947306 15.000000
      vertex 1.518981 -3.854200 0.000000
      vertex 1.095996 -3.947306 0.000000
    endloop
  endfacet
  facet normal -0.108120 0.994138 0.000000
    outer loop
      vertex 0.665423 -3.994134 15.000000
      vertex 1.095996 -3.947306 15.000000
      vertex 1.095996 -3.947306 0.000000
    endloop
  endfacet
  facet normal -0.108120 0.994138 0.000000
    outer loop
      vertex 0.665423 -3.994134 15.000000
      vertex 1.095996 -3.947306 0.000000
      vertex 0.665423 -3.994134 0.000000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 0.232312 -3.994134 15.000000
      vertex 0.665423 -3.994134 15.000000
      vertex 0.665423 -3.994134 0.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 0.232312 -3.994134 15.000000
      vertex 0.665423 -3.994134 0.000000
      vertex 0.232312 -3.994134 0.000000
    endloop
  endfacet
  facet normal 0.108120 0.994138 0.000000
    outer loop
      vertex -0.198260 -3.947306 15.000000
      vertex 0.232312 -3.994134 15.000000
      vertex 0.232312 -3.994134 0.000000
    endloop
  endfacet
  facet normal 0.108120 0.994138 0.000000
    outer loop
      vertex -0.198260 -3.947306 15.000000
      vertex 0.232312 -3.994134 0.000000
      vertex -0.198260 -3.947306 0.000000
    endloop
  endfacet
  facet normal 0.214970 0.976621 0.000000
    outer loop
      vertex -0.621246 -3.854200 15.000000
      vertex -0.198260 -3.947306 15.000000
      vertex -0.198260 -3.947306 0.000000
    endloop
  endfacet
  facet normal 0.214970 0.976621 0.000000
    outer loop
      vertex -0.621246 -3.854200 15.000000
      vertex -0.198260 -3.947306 0.000000
      vertex -0.621246 -3.854200 0.000000
    endloop
  endfacet
  facet normal 0.319301 0.947653 0.000000
    outer loop
      vertex -1.031685 -3.715907 15.000000
      vertex -0.621246 -3.854200 15.000000
      vertex -0.621246 -3.854200 0.000000
    endloop
  endfacet
  facet normal 0.319301 0.947653 0.000000
    outer loop
      vertex -1.031685 -3.715907 15.000000
      vertex -0.621246 -3.854200 0.000000
      vertex -1.031685 -3.715907 0.000000
    endloop
  endfacet
  facet normal 0.419890 0.907575 0.000000
    outer loop
      vertex -1.424766 -3.534048 15.000000
      vertex -1.031685 -3.715907 15.000000
      vertex -1.031685 -3.715907 0.000000
    endloop
  endfacet
  facet normal 0.419890 0.907575 0.000000
    outer loop
      vertex -1.424766 -3.534048 15.000000
      vertex -1.031685 -3.715907 0.000000
      vertex -1.424766 -3.534048 0.000000
    endloop
  endfacet
  facet normal 0.515554 0.856857 0.000000
    outer loop
      vertex -1.795881 -3.310756 15.000000
      vertex -1.424766 -3.534048 15.000000
      vertex -1.424766 -3.534048 0.000000
    endloop
  endfacet
  facet normal 0.515554 0.856857 0.000000
    outer loop
      vertex -1.795881 -3.310756 15.000000
      vertex -1.424766 -3.534048 0.000000
      vertex -1.795881 -3.310756 0.000000
    endloop
  endfacet
  facet normal 0.605174 0.796093 0.000000
    outer loop
      vertex -2.140677 -3.048648 15.000000
      vertex -1.795881 -3.310756 15.000000
      vertex -1.795881 -3.310756 0.000000
    endloop
  endfacet
  facet normal 0.605174 0.796093 0.000000
    outer loop
      vertex -2.140677 -3.048648 15.000000
      vertex -1.795881 -3.310756 0.000000
      vertex -2.140677 -3.048648 0.000000
    endloop
  endfacet
  facet normal 0.687699 0.725996 0.000000
    outer loop
      vertex -2.455114 -2.750798 15.000000
      vertex -2.140677 -3.048648 15.000000
      vertex -2.140677 -3.048648 0.000000
    endloop
  endfacet
  facet normal 0.687699 0.725996 0.000000
    outer loop
      vertex -2.455114 -2.750798 15.000000
      vertex -2.140677 -3.048648 0.000000
      vertex -2.455114 -2.750798 0.000000
    endloop
  endfacet
  facet normal 0.762162 0.647386 0.000000
    outer loop
      vertex -2.735505 -2.420697 15.000000
      vertex -2.455114 -2.750798 15.000000
      vertex -2.455114 -2.750798 0.000000
    endloop
  endfacet
  facet normal 0.762162 0.647386 0.000000
    outer loop
      vertex -2.735505 -2.420697 15.000000
      vertex -2.455114 -2.750798 0.000000
      vertex -2.735505 -2.420697 0.000000
    endloop
  endfacet
  facet normal 0.827689 0.561187 0.000000
    outer loop
      vertex -2.978561 -2.062216 15.000000
      vertex -2.735505 -2.420697 15.000000
      vertex -2.735505 -2.420697 0.000000
    endloop
  endfacet
  facet normal 0.827689 0.561187 0.000000
    outer loop
      vertex -2.978561 -2.062216 15.000000
      vertex -2.735505 -2.420697 0.000000
      vertex -2.978561 -2.062216 0.000000
    endloop
  endfacet
  facet normal 0.883512 0.468408 0.000000
    outer loop
      vertex -3.181434 -1.679556 15.000000
      vertex -2.978561 -2.062216 15.000000
      vertex -2.978561 -2.062216 0.000000
    endloop
  endfacet
  facet normal 0.883512 0.468408 0.000000
    outer loop
      vertex -3.181434 -1.679556 15.000000
      vertex -2.978561 -2.062216 0.000000
      vertex -3.181434 -1.679556 0.000000
    endloop
  endfacet
  facet normal 0.928977 0.370138 0.000000
    outer loop
      vertex -3.341745 -1.277206 15.000000
      vertex -3.181434 -1.679556 15.000000
      vertex -3.181434 -1.679556 0.000000
    endloop
  endfacet
  facet normal 0.928977 0.370138 0.000000
    outer loop
      vertex -3.341745 -1.277206 15.000000
      vertex -3.181434 -1.679556 0.000000
      vertex -3.341745 -1.277206 0.000000
    endloop
  endfacet
  facet normal 0.963550 0.267528 0.000000
    outer loop
      vertex -3.457615 -0.859882 15.000000
      vertex -3.341745 -1.277206 15.000000
      vertex -3.341745 -1.277206 0.000000
    endloop
  endfacet
  facet normal 0.963550 0.267528 0.000000
    outer loop
      vertex -3.457615 -0.859882 15.000000
      vertex -3.341745 -1.277206 0.000000
      vertex -3.457615 -0.859882 0.000000
    endloop
  endfacet
  facet normal 0.986826 0.161782 0.000000
    outer loop
      vertex -3.527684 -0.432476 15.000000
      vertex -3.457615 -0.859882 15.000000
      vertex -3.457615 -0.859882 0.000000
    endloop
  endfacet
  facet normal 0.986826 0.161782 0.000000
    outer loop
      vertex -3.527684 -0.432476 15.000000
      vertex -3.457615 -0.859882 0.000000
      vertex -3.527684 -0.432476 0.000000
    endloop
  endfacet
  facet normal 0.998533 0.054138 0.000000
    outer loop
      vertex -3.551132 -0.000000 15.000000
      vertex -3.527684 -0.432476 15.000000
      vertex -3.527684 -0.432476 0.000000
    endloop
  endfacet
  facet normal 0.998533 0.054138 0.000000
    outer loop
      vertex -3.551132 -0.000000 15.000000
      vertex -3.527684 -0.432476 0.000000
      vertex -3.551132 -0.000000 0.000000
    endloop
  endfacet
endsolid Mesh
```

### End result

![Vitara Example1](vitara_reardiskbrake/vitara1.jpg?raw=true "Vitara Example1")

![Vitara Example2](vitara_reardiskbrake/vitara2.jpg?raw=true "Vitara Example2")

