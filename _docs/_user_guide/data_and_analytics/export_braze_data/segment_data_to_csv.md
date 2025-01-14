---
nav_title: Export Segment Data to CSV
page_order: 2
---

# Exporting to CSV

To request a CSV export of user data from a segment, click on the "User Data" button on the top-right side while editing a segment:

![csvexport][1]

You can also request a CSV export from the main Segments page by clicking the gear icon on the right side to access this dropdown menu:

![csvexport2][2]

The CSV output contains the data from each user profile captured in the segment at the time of export. You can export any segment by clicking the gear icon and CSV export. Braze will generate the report in the background and email it to the user who is currently logged in.

If you have [linked your Amazon S3 credentials to Braze][26], then the CSV will instead be uploaded in your S3 bucket under the key `segment-export/SEGMENT_ID/YYYY-MM-dd/users-RANDOMSTRING.zip`. The link emailed to you will expire in a few hours and requires that you are logged into the dashboard to access it.

Data included in the exports:

- All User Data
    - User ID
    - First Name
    - Last Name
    - Timezone
    - City
    - Gender
    - Email Address
    - Phone Number
    - Number of Push Tokens
    - Twitter Username
    - Session Count
    - First Session
    - Last Session
    - Last App Version Used
    - In-App Purchase Total
    - Email Subscription Status
    - Device Info
    - Number of IDFAs
    - Number of IDFVs
    - Custom Events
    - Custom Attributes
- Email Addresses
    - User ID
    - First Name
    - Last Name
    - Email Address
    - Email Unsubscribe Date
    - Email Opt-in Date



[1]: {% image_buster /assets/img_archive/csvexport.png %}
[2]: {% image_buster /assets/img_archive/csvexport2.png %}
[26]: {{ site.baseurl }}/partners/technology_partners/data_and_infrastructure_agility/data_warehouses/aws_s3/#aws-s3-integration
