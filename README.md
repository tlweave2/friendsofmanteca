# Friends of Manteca Animal Shelter Website

A responsive, modern website for Friends of Manteca Animal Shelter (FOMAS) - a 501(c)(3) non-profit animal rescue organization in Manteca, California.

## 🌟 Live Demo

**[Visit the Live Website](https://tlweave2.github.io/friendsofmanteca/)**

## 📖 About

This website serves as the digital presence for Friends of Manteca Animal Shelter, a volunteer-led rescue organization that works in partnership with Manteca Animal Shelter to support animals through rescue, rehoming, spay/neuter programs, and education.

### Key Features

- 🏠 **Animal Adoption Showcase** - Live integration with Petfinder API to display available animals
- 📅 **Events Management** - Dynamic event calendar with Google Calendar integration support
- 💝 **Donation System** - Secure donation form with multiple payment options and PayPal integration
- 🐕 **Doggy Day Out Program** - Special program allowing community members to take shelter dogs on outings
- 📞 **Contact & Support** - Multiple ways for visitors to get involved and connect
- 📱 **Fully Responsive** - Optimized for desktop, tablet, and mobile devices

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Styling**: Custom CSS with CSS Grid and Flexbox
- **API Integration**: Petfinder API v2 for animal data
- **Payment Processing**: PayPal integration for secure donations
- **Hosting**: GitHub Pages
- **Design**: Modern, accessible design with custom color scheme

## 🚀 Features

### 🐾 Animal Management
- **Live Animal Data**: Real-time integration with Petfinder API
- **Search & Filter**: Filter animals by type, age, size, and other criteria
- **Detailed Profiles**: Individual animal cards with photos, descriptions, and contact info
- **Adoption Process**: Clear steps and downloadable forms

### 📅 Event System
- **Calendar Integration**: Ready for Google Calendar API integration
- **Event Categories**: Adoption events, fundraisers, educational programs, volunteer opportunities
- **RSVP System**: Built-in event registration functionality
- **Event Filtering**: Sort events by type and date

### 💰 Donation Platform
- **Multiple Amount Options**: Preset amounts ($25, $50, $100, $250, $300, $400, $500) and custom donation amounts
- **PayPal Integration**: Secure PayPal checkout system
- **Recurring Donations**: Support for one-time, weekly, monthly, quarterly, and yearly donations
- **Tax Information**: 501(c)(3) tax ID (33-3577449) and receipt system
- **Anonymous Donations**: Option for donors to remain anonymous

### 🎯 Special Programs
- **Doggy Day Out**: Interactive program section with downloadable forms
- **Foster Program**: Information and application process
- **Volunteer Opportunities**: Multiple ways to get involved
- **Spay & Neuter**: Affordable services information

## 📋 Organization Information

### Contact Details
- **Organization**: (FOMAS) Friends of Manteca Animal Shelter
- **Status**: 501(c)(3) Non-profit organization
- **Tax ID**: 33-3577449
- **Mailing Address**: 115 E WETMORE STREET, MANTECA, CA 95337
- **Email**: info@fomashelter.org
- **Website**: https://tlweave2.github.io/friendsofmanteca/

### Mission
Friends of Manteca Animal Shelter is a volunteer-led 501(c)(3) non-profit that is funded entirely by the financial support of generous donors and the dedication of time from committed volunteers. With community support, FOMAS provides more services to shelter animals in Manteca. Often animals come into shelters with conditions the facility is not equipped to address. Our mission is working toward providing those much-needed services allowing for successful rehoming. Additionally, we focus on reducing pet overpopulation through assistance with affordable Spay & Neuter programs, and work with severely injured and ill animals who are out of options through our emergency medical care programs.

## 🔧 Setup Instructions

### PayPal Integration Setup
1. Create a PayPal Business account
2. Go to PayPal Developer (developer.paypal.com)
3. Create or select an app to get your Client ID
4. Replace "YOUR_CLIENT_ID" in the donate.html script tag
5. Test the donation flow

### Petfinder API Setup
1. Register at Petfinder.com for API access
2. Get your API Key and Secret
3. Update the API credentials in animals.html and index.html
4. Configure the Manteca Animal Shelter organization ID

### Google Calendar Integration
1. Set up Google Calendar API access
2. Get your Calendar ID and API Key
3. Update the credentials in events.html
4. Configure calendar sync

## 📁 File Structure

```
friendsofmanteca/
├── index.html              # Homepage with featured animals
├── aboutus.html            # About us page with mission and programs
├── animals.html            # Available animals from Petfinder API
├── donate.html             # Donation page with PayPal integration
├── events.html             # Events calendar
├── contact.html            # Contact form and information
├── img/                    # Images and logos
│   ├── fomas.png          # Main logo
│   └── fomas2.png         # Secondary logo
├── documents/              # Downloadable forms
│   └── doggy-day-out-form.pdf
└── README.md              # This file
```

## 💻 Development

### Local Development
1. Clone the repository
2. Open any HTML file in a web browser
3. For API testing, serve files through a local server (due to CORS restrictions)

### Deployment
The site is automatically deployed via GitHub Pages from the main branch.

## 🎨 Design System

### Color Palette
- **Primary**: #df9588 (Warm coral)
- **Primary Dark**: #c57b6d (Darker coral)
- **Background**: #9f9a9a (Neutral gray)
- **Light Gray**: #f5f5f5
- **White**: #ffffff
- **Black**: #000000
- **Text Dark**: #333333

### Typography
- **Font Family**: Arial, Helvetica, sans-serif
- **Headings**: 600 weight
- **Body**: 400 weight
- **Line Height**: 1.6

## 🤝 Contributing

This website is maintained for Friends of Manteca Animal Shelter. For updates or changes, please contact the organization directly.

## 📞 Support

For technical issues or content updates, please contact:
- **Email**: info@fomashelter.org
- **Organization**: (FOMAS) Friends of Manteca Animal Shelter

## 📄 License

This website is created for Friends of Manteca Animal Shelter, a 501(c)(3) non-profit organization. All content is property of FOMAS.

---

**Note**: This is a volunteer-driven, 100% donor-supported organization. Every donation helps make a difference, one animal at a time.