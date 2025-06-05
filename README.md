# Pregnancy Tracker for Home Assistant

Originally created by [alexives](https://github.com/alexives), this pregnancy tracker is an all-local solution that does not track and sell your information.<br>

This was originally posted on a [Home Assistant Community Post](https://community.home-assistant.io/t/pregnancy-tracking-privately-with-tempalate-sensors/270583), and is meant to provide you as much information as possible, allowing you to limit it to what you like by simpling omiting lines of code or removing modules from Lovelace.

***Note:** For the Dashboard (Lovelace) view, you will need to install the following (all are available via [HACS](https://hacs.xyz/)):
- [custom:text-action-element](https://github.com/custom-cards/text-action-element)
- [custom:card-templater](https://github.com/gadgetchnnel/lovelace-card-templater)
- [custom:gallery-card](https://github.com/TarheelGrad1998/gallery-card).

The code is a single dashboard view that can be added to an existing dashboard.

<br><br />
![Dashboard](images/Dashboard.jpeg)
<br><br />
### Sensors/Attributes Available
- Date of Next Checkup
- Number of days into pregnancy
- Number of days remaining in pregnancy
- Week into the pregnancy
- Day of the week
- Pregnancy Percent
- Fetal Length (inches)
- Fetal Weight (ounces/lbs)
- Trimester
- Fetal Development (week by week description of what's going on inside)

#### Baby Size Comparisons with Pictures
- Fruit
- Manly
- Geeky
- Food Cravings
- Dude Dad (no pictures)

#### Input Helpers
- First Day of Last Period: `input_datetime.pregnancy_last_period`
- Pregnancy Offset (for twins or non-standard pregnancies): `input_number.pregnancy_size_offset`

#### Data Sources
- [BabyCenter](https://www.babycenter.com/)
- [What To Expect](https://www.whattoexpect.com/)
- [Babysizer](https://babysizer.com/)
- [Verywell Family](https://www.verywellfamily.com/)
- [Mayo Clinic](https://www.mayoclinic.org/healthy-lifestyle/pregnancy-week-by-week/in-depth/hlv-20049471)
- [Dude Dad: A Dude's Guide to Baby Size Book by Taylor Calmus](https://www.dudedad.com/pages/dudes-guide-to-baby-size) 

### Contributors
Many thanks to everybody who helped with this project:
- [alexives](https://github.com/alexives) (original creator)
- [tango2590](https://github.com/tango2590) (primary repo maintainer)
- [raphi](https://community.home-assistant.io/u/raphi/summary)
