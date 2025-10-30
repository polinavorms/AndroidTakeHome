# AndroidTakeHome
Welcome to Zelt's Take Home task :) 

**Timebox**: 3-4 hours

**Goal**: Build a small Android app that lists people from a public API, supports search and details.

### Data Source
```
https://randomuser.me/api/?results=2000
```

Useful fields: `name.first`, `name.last`, `picture.thumbnail`, `picture.large`, `email`, `phone`, `location.city`, `location.country`.

### Acceptance Criteria
**People List**
1. Fetch and display people on first launch.
2. Each row shows: avatar, full name, city and country.
3. Add a search box at the top of the list. 

**Details**
1. Tapping a person opens a details screen with: large photo, full name, email, phone, city and country.
2. Include one small "delight" (for example, copy-to-clipboard for email or phone, or a subtle animation).
