/*
Military Time
Given a string that represents time in hours and minutes, convert the string to military time (if necessary).
Examples:
toMilitary("3:00pm") // "15:00"
toMilitary("9:15am") // "09:15"
toMilitary("12:00am") // "00:00"
toMilitary("04:00") // "04:00"
*/

function toMilitary(time) {
  // your code here...
  const timer = time.split(/:apm/)
  let hours = parseInt(timer[0]);
  if (time.includes('pm') && hours !==12) {
    hours += 12;
  } else if (time.includes('am') && hours ===12) {
    hours = 0;
  }else{
    return "wrong "
  }
  return 
}
