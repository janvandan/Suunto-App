# Suunto-App

Mes applis pour ma suunto ambit 3 peak

intRun %VMA

programmation de séances de fractionnés 

/* set your VMA or MAS in min/km */
VMA=3.43; /* TBD */

/* BEGIN Configuration Interval */
/*     prefix is used to set the interval target */
/*         warm (for warmup) */
/*         ACC (for accelerate) */
/*         XX% where XX is the %vma (%mas) targeting */
/*         ---% (for rest interval)
/*         cool (for cooldown) */
/*     RESULT is used to set the interval duration or distance */
/*         < 15 assume it's a distance (in km) */
/*         >= 15 assume it's a duration (in s) */
/*         could be set to SUUNTO_DURATION_PREV for the rest duration */
