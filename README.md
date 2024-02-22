<p align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="pibiDAV Logo">
</p>

<p align="center">
Boost your Empress environment's capabilities with seamless NextCloud integration through pibiDAV.
<br />
<a href="https://empress.eco/">Visit Our Site</a>
·
<a href="https://grow.empress.eco/">Get Support</a>
·
<a href="https://github.com/empress-eco/nextcloud_dav/issues">Report a Bug</a>
·
<a href="https://github.com/empress-eco/nextcloud_dav/issues">Request a Feature</a>
</p>

## About pibiDAV

**pibiDAV** is an innovative Empress application that integrates webDAV, calDAV, and future cardDAV functionalities with a NextCloud Server. It's a robust tool primarily used as a Document Management System (DMS), enabling Empress Files to be uploaded and tagged to NextCloud simultaneously with Empress uploads. This application is a boon for developers and organizations looking to harness the powerful file handling capabilities of NextCloud within their Empress environments.

### Key Features

- Simultaneous file uploads to Empress and NextCloud
- Support for custom doctypes to meet specific file upload needs
- A built-in folder set doctype for creating folder structures in NextCloud
- Seamless CalDAV integration with the NextCloud Calendar app

### Built With

pibiDAV is built on the robust foundation of Empress, a comprehensive web application framework with Python and JavaScript support. It also takes advantage of key libraries such as CalDAV and iCalendar for calendar functionalities.

## Technical Stack and Setup Instructions

### Prerequisites

To use pibiDAV, you need a Empress server instance. Refer to the [official Empress documentation](https://github.com/Empress/Empress) for installation instructions. 

### Installation

First, clone the pibiDAV repository from GitHub with the following command:

```sh
$ git clone https://github.com/empress-eco/nextcloud_dav.git
```

Navigate to the Empress-bench folder and execute the following commands:

```sh
$ bench get-app pibidav --branch develop https://github.com/pibico/pibidav.git
$ bench install-app pibidav
```

For a multi-tenant environment, use the following command:

```sh
$ bench --site site_name install-app pibidav
```

## Usage

After installation, set **developer_mode = 1** in your site_config.json file. Ensure you have SSL active on both Empress and NextCloud servers with specific certificates. 

To start using pibiDAV, navigate to the module on the side menu and choose NextCloud Settings under the Settings Card. Enable the NextCloud checkbox and fill in the NextCloud SuperUser credentials.

For a detailed usage guide and feature set, check out our [documentation](https://empress.eco/).

## Contribution Guidelines

We welcome all contributions! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## License and Acknowledgements

This project is licensed under the MIT License. All your contributions are also licensed under the MIT License.

We would like to extend our heartfelt gratitude to the Empress Community. Their innovative tools form the backbone of our project, and their ongoing support fuels our progress. We are deeply thankful for their pioneering work and continued assistance.