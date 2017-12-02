### Booked Appointments {#booked}



[Booked](https://getbooked.io/)is a powerful and easy-to-use appointment booking plugin for WordPress.

#### Create a Profile Page

If you would like your customers to manage their own appointments and edit their profile, you'll want to activate the profile page. It's an easy process though, just follow the guide below:

1. Create a page and give it a title.
   **Profile**
   works too, but it can be whatever you want it to be.
2. Add the
   **\[booked-login\]**
   shortcode to the page so your users can log in to view their profile.
3. Go to the
   **Booked Settings**
   panel
   **\(Appointments **
   **&gt;**
   ** Settings\)**
   and choose this new page from the dropdown in the
   **General Settings**
   tab.

Just after installing the Contact Form 7 plugin, you’ll see a default form named**Contact form 1**and a code like this:

##### General Settings

* profile page
  as described above, you will choose the page you want to use for the profile from this dropdown;
* time slot intervals
  when creating your default time slots \(described below\), you can choose the intervals at which you can choose your time slots. Just change it with this dropdown.

##### User Emails

All emails can be turned off one by one by simply removing the content of the email in the fields. If nothing is there then no email is sent. All emails have special tokens you can use in place of actual content. This content is placed into the email when it gets sent. The tokens are listed above each email form.

* registration
  this is the email that is sent to your new users, welcoming them to your website;
* appointment confirmation
  this email is sent to the user when they book an appointment as a confirmation that the appointment has been submitted;
* appointment approval
  this is the email that is sent to the user when their appointment is approved;
* appointment cancellation
  this is the email that is sent to the user if their appointment is cancelled by the website admin.

##### Appointment Creation

The power of**Booked**is that your customers can pick and choose from available time slots when they would like to book their appointment. However, in some cases the admin needs this power. You can create appointments quickly and easily using the appointment calendar:

* click
  **Appointments**
  in the admin panel;
* you will see a big calendar, showing the current month \(if the current date is wrong, please make sure the correct time zone is selected from
  **Settings **
  **&gt;**
  ** General**
  \);
* pick the day on which you want to book the appointment;
* choose a time slot and click the
  **New Appointment**
  button;
* if this is a current customer, you can simply select them from the user dropdown;
* if this is a new customer, you can quickly add them as a new user by using the registration fields. The first name and email are the only required fields;
* when the appointment is booked, the user will get an email welcoming them to the site \(with a username/password\) as well as an appointment confirmation email. These emails can be customized/turned off from the
  **Booked Settings**
  panel.

##### Appointment Cancellation

To cancel someone's appointment, simply find the appointment on the calendar and click the**×**next to their name in the time slot from which you want to remove them.

#### Shortcode

```

```

#### Default Time Slots

Setting your default time slots is at the heart of the Booked plugin. Each day is assigned to default time slots. For example, if your business is open on Monday – Friday from 8:00am – 4:00pm and you have 2 employees available every hour, you would create 2 times slots every hour from 8–4, Monday – Friday.

##### Bulk Time Slot Entry

To quickly add a bunch of time slots, you can use the Bulk time slot entry option:

* click
  **Add**
  at the top of the day you're adding time slots to;
* switch to the
  **Bulk**
  tab;
* for the
  **Start time**
  , select 8:00am;
* for the
  **End time**
  , select 4:00pm;
* leave the next dropdown as
  **Every 1 hour**
  to set your time slots every hour;
* choose
  **2 time slots**
  as the last option, and then click "
  **Add**
  ;
* your available time slots for that day will then be added and your customers can start booking the appointments!
* ##### Single Time Slot Entry

  Alternatively, you can add a single time slot to any day/time:

  * click
    at the top of the day you're adding time slots to;
  * choose a
    **Start time**
    and
    **End time**
    and then select how many time slots you want to add;
  * click
    **Add**
    and that time slot entry will be added as a default for that day.

  #### Adding Custom Time Slots

  * go to the Booked Settings panel and then go to the
    **Custom Time Slots**
    tab;
  * click the
    **Add Date\(s\)**
    button;
  * choose the calendar you want to use \(if applicable\);
  * choose the
    **Start Date**
    ;
  * if this is a one day setting, you can leave the
    **End Date**
    blank. If this is a date range, choose the
    **End Date**
    ;
  * to add a single time slot, click the
    **+ Single Time Slot**
    button. To bulk add time slots, click the
    **+ Bulk Time Slots**
    button;
  * for single time slots, you'll choose how many available appointments for this time slot and then you'll choose the start and end times. Alternatively, you can check the
    **All day**
    checkbox to make this an all day time slot;
  * to add bulk time slots, choose how many available appointments there are, choose a start and end time for the entire span of your day, choose the time between each slot if you need a 10 minute break for example. Then choose the interval for the time slots to be entered.

  For more information, please visit[video tutorial.](https://www.youtube.com/watch?v=bD-BcS7p4vQ)

  #### Adding Vacation/Closed Dates

  * go to the Booked Settings panel and then go to the
    **Custom Time Slots**
    tab;
  * click the
    **Add Date\(s\)**
    button;
  * choose the calendar you want to use \(if applicable\);
  * choose the
    **Start Date**
    ;
  * if this is a one day setting, you can leave the
    **End Date**
    blank. If this is a date range, choose the
    **End Date**
    ;
  * check the
    **Disable appointments**
    checkbox to make this a vacation/closed date.;
  * that's it.
  * For more information, please visit[video tutorial](https://www.youtube.com/watch?v=0n5zdYoaHzc).



