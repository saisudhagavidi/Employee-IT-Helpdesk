# Assignment Groups

The Employee IT Helpdesk application uses assignment groups to route incidents and service requests to the appropriate IT support teams.

## Groups Created

| Group               | Purpose                                                             |
| ------------------- | ------------------------------------------------------------------- |
| IT Helpdesk         | Handles general IT support and first-level incidents                |
| Network Support     | Handles network, Wi-Fi, VPN and connectivity issues                 |
| Hardware Support    | Handles laptops, desktops, peripherals and hardware-related issues  |
| Software Support    | Handles software installation and software-related issues           |
| Security Support    | Handles security-related incidents and access/security concerns     |
| Application Support | Handles application-specific issues and application access requests |

## Assignment Mapping

The planned incident assignment logic is:

| Incident Category | Assignment Group    |
| ----------------- | ------------------- |
| Hardware          | Hardware Support    |
| Software          | Software Support    |
| Network           | Network Support     |
| Security          | Security Support    |
| Application       | Application Support |
| Other             | IT Helpdesk         |

## Purpose

These groups will be used later for:

* Automatic incident assignment
* Service request fulfillment
* Flow Designer workflows
* Notifications
* SLA management
* Role-based access
* IT support reporting
