# jc3mp-timechange
Based on JC2MP's TimeChange - https://github.com/Jasonmrc/TimeChange


Adds clientside events when seconds and minutes pass.  Great for doing things every second, minute, etc.

Usage:

jcmp.ui.AddEvent('SecondTick', (seconds) => {
  // One second has passed
})


jcmp.ui.AddEvent('MinuteTick', (minutes) => {
  // One minute has passed
})


