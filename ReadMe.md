# Fantastical Tools

## Usage

### Create A Calendar Event Without Notes

* Create the event `event text` at 13:00 on a calendar that starts with `f` (Say, Family Shared Calendar).

        f event text monday 13:00 \f
* Create the event `event text` at 13:00 with a URL of `http://foo.com` on a calendar that starts with `f` (Say, Family Shared Calendar).
        
        f event text monday 13:00 http://foo.com \f


### Create A Calendar Event With Notes

* Create the event `event text` at 13:00 with notes `note text` on a calendar that starts with `f` (Say, Family Shared Calendar).

        f event text monday 13:00 ; note text /f
    * NB: `<space>;<space>` is the required delimiter.[^1]
* Create the event `event text` at 13:00 with URL of `http://foo.com`and notes `note text` on a calendar that starts with `f` (Say, Family Shared Calendar).

        f event text monday 13:00 http://foo.com ; note text /f
        
* Create the event `event text` at 13:00 with  notes `note text` and contains the URL `http://foo.com`on a calendar that starts with `f` (Say, Family Shared Calendar).

        f event text monday 13:00 ; note text http://foo.com /f

### Create A Reminder Event Without Notes

* Create the reminder `reminder text` at 13:00 on a calendar that starts with `r` (Say, Reminders).

        ft reminder text monday 13:00 \r        
* Create the reminder `reminder text` at 13:00 with a URL of `http://foo.com` on a calendar that starts with `r` (Say, Reminders).
        
        f reminder text monday 13:00 http://foo.com \r

### Create A Reminder Event With Notes

* Create the event `reminder text` at 13:00 with notes `note text` on a calendar that starts with `r` (Say, Reminders).
        
        ft reminder text monday 13:00 ; note text /r
    * Again, note `<space>;<space>` delimiter.

* Create the reminder `reminder text` at 13:00 with URL of `http://foo.com`and notes `note text` on a calendar that starts with `r` (Say, Reminders).

        ft reminder text monday 13:00 http://foo.com ; note text /r


## Keyword Definitions

### Basic Creation Actions

**f** :
    Create a calendar event.

**ft** :
    Create a new reminder.

### Quick Events

**fdst** :
    Create a calendar event for Daddy / Son Time.

### Quick Reminders

**ft7** :
    Create a new reminder at 07:00.
    

**ft11** :
    Create a new reminder at 011:30.
    

**ft13** :
    Create a new reminder at 13:30.
    

**ft16** :
    Create a new reminder at 16:00.
    
### Searching - Basic Queries 

**fs** :
    Searches Fantastical for given query.
    
**fsbd** :
    Displays Birthdays. 
    
**fsh** :
    Displays Holidays.[^2]  
    
### [Searching Fantastical](http://shmow.us/y494+) Proof of Concept

#### Creating Actions For Future Search

**fr3** :
    Create a 3DS calendar event for my *Release Dates* calendar (Adds template notes).
    
**frv** :
    Create a PS Vita calendar event for my *Release Dates* calendar (Adds template notes).
    
**frv** :
    Create a Book calendar event for my *Release Dates* calendar (Adds template notes).
    
**frv** :
    Create a Movie calendar event for my *Release Dates* calendar (Adds template notes).

#### Displaying Known Search Tokens

**fsfm** :
    Displays all *Type: Medical* calendar events.
    
**fs3** :
    Displays *Platform: 3DS* calendar events (release date).
    
**fsv** :
    Displays *Platform: Vita* calendar events (release date).
    
**fsg** :
    Displays all *Type: Video Game* calendar events (release date).


**fsb** :
    Displays all *Type: Book* calendar events (release date).

**fsm** :
    Displays all *Type: Movie* release date calendar events (release date).
