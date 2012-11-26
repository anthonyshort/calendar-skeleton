
# calendar-skeleton

  Template for anthonyshort/calendar. Gives you basic HTML and CSS to construct a calendar. 

## Installation

    $ component install anthonyshort/calendar-skeleton

## API

Set the template on the Calendar either on the prototype or send it in the options when creating a calendar:

    var Calendar = require('calendar');
    var template = require('calendar-skeleton');
    
    // On the prototype
    Calendar.prototype.template = template;
    
    // or in the options
    var picker = new Calendar({ template: template });

## License

  MIT
