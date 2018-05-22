# Web Developer Take-Home Project | Sense
This take-home project is intended to give us an idea of the way you approach your work as a web developer. We estimate it should take no longer than two hours. We do understand that you may have limited time, so please do reach out with feedback if this will not fit into your schedule.

Moreso than deep technical understanding, we will be looking for attention to detail, organization, and thoughtful communication.

### Installation:
  - Clone and install from <repository host>
  - Install dependencies with either `yarn install` or `npm install` (note, this repository was created with node `v8.9.2`. If you have issues installing, please try upgrading your version of node first.)
  - Start the development server with either `yarn start` or `npm start`. This will reload your changes live as you are working.

### Deliverables:
  * Please build a mobile-responsive navbar for a hypothetical web application (it may or may not be based on our real web application 😄).
  * In desktop view, each icon should have a text label (see style guide for font sizes):
    - Now, `now.svg`
    - Usage, `usage.svg`
    - Meter, `meter.svg`
    - Devices, `devices.svg`
    - Settings, `settings.svg`
    - Feedback, `feedback.svg`
  * At the mobile breakpoint, this sidebar should switch to being a fixed menu at the bottom of the page (see attached gif for behavior).
  * The mobile version should have the labels removed with the icons remain centered vertically.
  * You may use any modern CSS features at your disposal. This project does not need to be widely compatible, but a short description of how you would approach browser compatibility would be appreciated.
  * When you have completed the project, please fill out the attached `summary.md` and describe your approach to the project, any sticking points you found, and how you resolved them.

*NOTE:* _It should be possible to accomplish all of this using only html and CSS. That said, if you have extra time and would like to demonstrate some JavaScript skills, feel free to move on to the bonus question below._

##### Bonus:
  * Our web application needs to know which tab we are currently looking at. For this example, consider the current tab to be a query parameter: `tab` that will be set to a string representing the current tab. For example, a URL like: `https://localhost:8000?tab=meter` should highlight the "meter" icon and label (in Desktop mode).

*NOTE:* _Please focus on the above deliverables first and only complete this bonus question if you have time. We would much rather see a solid showing on the core. _

### Style guide:
  * Please see the `/assets` folder for included icons.
  * Useful variables:
    - Base Font Size: 16px (Browser Default)
    - Mobile breakpoint: `480px`
    - Sense Red: `#F9461C`
    - Sense Black: `#353535`
    - Sidebar Width / Height (in Mobile): 4rem
    - Font Size: 0.75rem;
