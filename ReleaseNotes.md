## Changes
### OcSupportPkg
- OcAppleBootCompatLib: Update NVRAM page limit and disable SKL+ hacks
- OcAppleKeyMapLib: Split Aggregator and DB functions
- OcAppleKeyMapLib and OcAppleEventLib: Initial import
- OcAppleBootCompatLib: Implement DevirtualiseMmio
- OcAppleKernelLib: Added notes for HWP and _xcpm_core_scope_msrs patch
- OcMachoLib: Remove unused variable
- OcMachoLib: Revert incorrect changes from last commit
- OcMachoLib: Prevent accidential VTable sym matches via overflow
- OcMachoLib: Fix security and parsing issues
- OcGuardLib: Introduce OC_ALIGNOF and deprecate OC_ALIGNED
