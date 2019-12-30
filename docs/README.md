## Overview

The goal of the app is booking users

Each [vehicles](vehicles.md), [users](users.md), and [bookings](bookings.md) are grouped into [clients](clients.md). Therefore, each client will have their own separate sets of vehicles, users, and bookings. See [clients](clients.md) for more info.

The app has multiple user [roles](/users.md#Roles) with varying [permissions](/permissions.md). The four roles and their general functions in the app are as follows:

**Master**

- Divide the other roles into [clients](/clients.md).

- Provide [locations](/locations.md) to clients.

- Provide [vehicles](/vehicles.md) to clients.

- Manage all bookings, locations, users, vehicles, and clients.

**Admin**

- Manage users, vehicles, bookings, and locations within its [client](/clients.md).

- Create accounts within its [client](/clients.md).

**Key Manager**

- Manage bookings, and vehicle availability.

**Guest**

- Create and submit booking requests within its [client](/clients.md).

## Sidebar Navigation


#### Home

Contains a dashboard of the current status of vehicles, bookings, accidents, and users.

:closed_lock_with_key: Accessible by *Everyone*

#### Bookings

This is where Master, Admin, and Key Manager can manage bookings. Guests can create a booking request here.

See [Bookings](/bookings.md).

:closed_lock_with_key: Accessible by *Everyone*

#### Locations

See [Locations](/locations.md).

:closed_lock_with_key: Accessible by *Everyone*

#### Users

See [Users](/users.md).

:closed_lock_with_key: Accessible by *Master*, *Admin*, *Key Manager*

#### Vehicles

:closed_lock_with_key: Accessible by *Everyone*

See [Vehicles](/vehicles.md).

#### Accidents

:closed_lock_with_key: Accessible by *Everyone*

See [Accidents](/accidents.md).

#### Clients

:closed_lock_with_key: Accessible by *Master*

See [Clients](/clients.md).

#### Reports

:closed_lock_with_key: Accessible by *Master*, *Admin*, *Key Manager*

See [Reports](/reports.md).

#### Settings

:closed_lock_with_key: Accessible by *Everyone*

See [Settings](/settings.md).
