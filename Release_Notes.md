---
pagetitle: Release Notes for LSM6DSO Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for LSM6DSO Component Driver
Copyright &copy; 2021 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the LSM6DSO component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 18-June-2021</label>
<div>			

## Main changes

### First release

- First official release [ref. DS v2.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V2.0.0 / 19-April-2023</label>
<div>			

## Main changes

- Fixed wrong implementation of lsm6dso_interrupt_mode_get.
- Fix typo in TAG enum, add missing TAG enum (timestamp) in getter
- Fix mistakes in docs for setters and getters
- Fixed most mcuastyle errors

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V2.1.0 / 26-May-2023</label>
<div>			

## Main changes

- review read/write reg ret value checks
- Use a single lsm6dso_fifo_sh_batch_slave_xxx() API for all targets
- Use a single lsm6dso_sh_slv_cfg_read() API for all targets
- read sh status from mainpage
- Change lsm6dso_mem_bank_set() API

##

</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V2.2.0 / 09-Nov-2023</label>
<div>			

## Main changes

- Fix "maybe uninitialized variable" warnings

##

</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V3.0.0 / 18-Jan-2024</label>
<div>

## Main changes

- Add "const" to ctx arg for all APIs

##

</div>

<input type="checkbox" id="collapse-section6" checked aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V3.0.1 / 11-Mar-2024</label>
<div>

## Main changes

- fix typo error in reg.c

##

</div>
:::

:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on LSM6DSO,
visit:
[LSM6DSO](https://www.st.com/content/st_com/en/products/mems-and-sensors/inemo-inertial-modules/lsm6dso.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 2.0">Info</abbr>
:::
:::
</footer>
