Christopher Donnelly

1)Added a new struct to "tests.c" for mega alarm.

{"alarm-mega", test_alarm_mega},


2)Added test_func to "tests.h" for mega alarm.

extern test_func test_alarm_mega;


3)Added new function to "alarm-wait.c". for mega alarm.

void
test_alarm_mega (void) 
{
  test_sleep (5, 70);
}
