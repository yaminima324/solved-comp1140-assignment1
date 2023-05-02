Download Link: https://assignmentchef.com/product/solved-comp1140-assignment1
<br>
Data Requirements:

<strong>Catalogue</strong>

The School of SEEC maintains information about its physical and online resources. SEEC have physical resources which students can borrow/loan such as cameras, speakers, phones and CDs. SEEC also have online resources which can be used such as various software that students can have access to if required.

<strong>Collections</strong>

The School have many collections of items in each respective location. A collection contains a unique name – “ES105 – Speaker”, etc. and provides the location where the collection exists physically in the building. Each physical item belongs to a collection within the School of SEEC. Likewise, the School of SEEC also provides information as to where to access and download software for student use. Each software item is a part of a collection which exists virtually and is arranged into different categories depending on the course (e.g. Engineering, Computing, etc.) that the software is related to.

<strong>Resources</strong>

The School of SEEC have many resources that they can loan students during the duration of their degree to assist them in their study or to use during their assignments. Every resource has:

<ul>

 <li>a resource ID (which is unique)</li>

 <li>a description of the item</li>

 <li>a status (e.g. ‘in use’, ‘maintenance’, ‘available’, ‘borrowed’, ‘lost’, ‘damaged’, etc.)</li>

</ul>

There are two types of resources students can use; moveable and non-moveable. Moveable resources include items such as cameras, microphones, speakers, etc. Moveable resources have a:




<ul>

 <li>name</li>

 <li>make</li>

 <li>manufacturer</li>

 <li>model</li>

 <li>year</li>

 <li>asset value</li>

</ul>

<strong> </strong>

For example, the SEEC resource database about would maintain information about cameras. Information on cameras maintained by the School include:




<ul>

 <li>Brand of camera (Canon, Nikon, Sony)</li>

 <li>Type of camera (camcorder, DSLR, action)</li>

 <li>Camera lenses (standard/general purpose, wide angle)</li>

 <li>Charge time and battery life</li>

 <li>Colour</li>

 <li>Model Number</li>

 <li>Serial Number</li>

 <li>Storage location of the cameras depending on what is loaned/used more.</li>

</ul>




Non-movable resources are resources such as classrooms, laboratories, etc. Each immovable resource has:




<ul>

 <li>maximum person capacity</li>

 <li>room name</li>

 <li>building</li>

 <li>campus</li>

</ul>










Each resource is placed into a category, such as ALL cameras, ALL speakers, etc. Each category has a:




<ul>

 <li>unique code</li>

 <li>name</li>

 <li>description</li>

 <li>max time allowed to borrow/book (in days and/or hours)</li>

</ul>




<strong>Location</strong>

All resources have a location where they are situated that can accessed by staff members and student members alike. These locations have a:




<ul>

 <li>unique ID</li>

 <li>room</li>

 <li>building</li>

 <li>camp</li>

</ul>




<strong>Loan</strong>

Lending and reservation rights are offered to students by staff who are enrolled in courses offered by SEEC. These students and staff are known as “members” in the system. Members have a:




<ul>

 <li>unique ID (student or staff number)</li>

 <li>name</li>

 <li>address</li>

 <li>phone number</li>

 <li>email</li>

 <li>status (‘active’, ‘disabled’)</li>

 <li>comments field</li>

</ul>




Student members enroll in courses offered by SEEC. Course information about course offerings and student enrollments are maintained. A course offering has a:




<ul>

 <li>offering ID (which is unique)</li>

 <li>course ID (which is unique)</li>

 <li>name</li>

 <li>semester offered</li>

 <li>year offered</li>

 <li>course beginning/end date</li>

</ul>

<strong> </strong>

<strong>Privilege</strong>

Staff members can borrow/reserve resources. Staff have no limits on the number of resources that staff can use. Students are granted privileges on what they can borrow/reserve depending on the course they are enrolled in. Courses are assigned privileges to different categories of resources. Each privilege has a:




<ul>

 <li>name</li>

 <li>description</li>

 <li>a privilege category</li>

 <li>maximum number of resources that a student member can borrow/book at any given time</li>

</ul>




A member can loan moveable resources (such as cameras, speakers, etc.) if their privileges allow it. Information about the resource when it is loaned is maintained for the duration of it loan.

<strong>New Acquisitions</strong>

New acquisitions can be made to the School by a student or staff member. An acquisition contains:




<ul>

 <li>a person requesting acquisition</li>

 <li>an item name</li>

 <li>make</li>

 <li>manufacturer</li>

 <li>model</li>

 <li>year</li>

 <li>a description of the required item</li>

 <li>its urgency</li>

</ul>




The administrator of the system assigns values to the acquitted item such as:




<ul>

 <li>status (‘acquired’, ‘pending’, etc.)</li>

 <li>a fund code</li>

 <li>vendor code</li>

 <li>price</li>

 <li>other notes pertaining to the request</li>

</ul>

<strong> </strong>

<strong>Reservations</strong>

Resources can be reserved by members as long as their privileges allow them to borrow/book that resource. The resource will be booked for pickup/use by the student or staff member at the requested date and time after a reservation is made. Reservations have the date and time the item is required and a due date and time. No two reservations should ever conflict as that becomes problematic for one of the members attempting to borrow/book the resource.




Transaction Requirements:

<strong>Data Manipulation Operations</strong>

<ul>

 <li>Insert/update/delete an item in the database</li>

 <li>Insert/update/delete a copy of item in the database</li>

 <li>Insert/update/delete the status of an item</li>

 <li>Insert/update/delete an online information source</li>

 <li>Insert/update/delete staff of the School of SEEC</li>

 <li>Insert/update/delete location of a resource</li>

 <li>Insert/update/delete members</li>

 <li>Insert/update/delete member information</li>

 <li>Insert/update/delete acquisition items</li>

 <li>Insert/update/delete reservations</li>

</ul>

<strong>Queries</strong>

<ul>

 <li>Search for an item based on brand, title, serial number, keyword and/or publisher</li>

 <li>List current loans by a specific member</li>

 <li>List frequently loaned items for each semester</li>

 <li>List members who have loaned an item over a duration of time</li>

 <li>List new acquisitions made by staff or student members</li>

 <li>Fines report containing information about fines imposed and members fined</li>

 <li>Provide information about student member privileges</li>

 <li>Provide information about reservation dates of resources</li>

 <li>Provide information about the privileges members have</li>

 <li>Provide information about the maximum possible loans a student member can take out</li>

</ul>










Business Rules:

<ol>

 <li><strong>Expiration of Student Member Access</strong>

  <ul>

   <li>A student’s borrowing privileges are taken away when they finish their enrolled course.</li>

   <li>When the date is later than the end date, they are automatically taken away.</li>

   <li>The status of the student member is set to ‘disabled’</li>

  </ul></li>

 <li><strong>Maximum number of items loaned or reserved at any one time</strong>

  <ul>

   <li>A student member cannot borrow, or reserve more than the maximum number of items specified in his/her privileges at any given time</li>

   <li>Staff members have precedence over student members regarding loaning resources</li>

  </ul></li>

 <li><strong>Late returns by student member penalties</strong>

  <ul>

   <li>Each student member has a default set of points earned at the beginning of their course (12 to start with)</li>

   <li>For each incurred day that the item is overdue, a penalty of 3 points is given, which is deducted from the total amount that student member has</li>

   <li>When the points come to 0, member status of that student is disabled, and borrowing/reservation privileges are revoked</li>

  </ul></li>

 <li><strong>Cancellation of Reservations</strong>

  <ul>

   <li>A reserved item is cancelled if it is not collected by the member on the day of the required due date</li>

   <li>Non-cancellation of a reservation by a member means 1 point is deducted from the member’s total</li>

   <li>Administrators can also cancel any reservation as they hold the right to do so</li>

  </ul></li>

 <li><strong>Borrowing/Reservation Periods</strong>

  <ul>

   <li>The duration of the borrowing/reservation periods, being either number of days or hours, is determined by the category to which the item belongs</li>

  </ul></li>

</ol>







<strong>ENTITY TYPES:</strong>

<table>

 <tbody>

  <tr>

   <td width="174">Entity Name</td>

   <td width="174">Description</td>

   <td width="174">Aliases</td>

   <td width="174">Occurrence</td>

  </tr>

  <tr>

   <td width="174">Catalogue</td>

   <td width="174">A database of resources that is used to search for loanable items</td>

   <td width="174">Database</td>

   <td width="174">Online database where the catalogue can be accessed</td>

  </tr>

  <tr>

   <td width="174">Resources</td>

   <td width="174">Items both physical and virtual that are used by students to aide their study</td>

   <td width="174">Borrowed Items</td>

   <td width="174">Physically stored in certain locationsVirtually stored online</td>

  </tr>

  <tr>

   <td width="174">Category</td>

   <td width="174">Describes a group of items which are similar/the same</td>

   <td width="174"> </td>

   <td width="174">Items are categorized so searching for them and loaning is more efficient</td>

  </tr>

  <tr>

   <td width="174">Location</td>

   <td width="174">Place where resources are kept</td>

   <td width="174"> </td>

   <td width="174">The place, physically or virtually, where a resource is stored</td>

  </tr>

  <tr>

   <td width="174">Movable Resources</td>

   <td width="174">Resources such as cameras, speakers, etc.</td>

   <td width="174"> </td>

   <td width="174">Loaned out by members of SEEC, either students or staff</td>

  </tr>

  <tr>

   <td width="174">Non-movable Resources</td>

   <td width="174">Resources such as classrooms, studios, laboratories, etc</td>

   <td width="174">Buildings/Rooms</td>

   <td width="174">Loaned out by members of SEEC, either students or staff</td>

  </tr>

  <tr>

   <td width="174">Loan</td>

   <td width="174">Borrowing an item/resource</td>

   <td width="174">Borrow</td>

   <td width="174">Items that are borrowed from SEEC</td>

  </tr>

  <tr>

   <td width="174">Reservations</td>

   <td width="174">Resources student and staff members request to loan</td>

   <td width="174"> </td>

   <td width="174">A member logs online and requests to loan a resource from SEEC</td>

  </tr>

  <tr>

   <td width="174">Members</td>

   <td width="174">A student or staff member</td>

   <td width="174">Students/staff</td>

   <td width="174">Members reserve resources</td>

  </tr>

  <tr>

   <td width="174">Students</td>

   <td width="174">Members that enroll into courses at the University</td>

   <td width="174">Members</td>

   <td width="174">Students make reservations to loan a resource</td>

  </tr>

  <tr>

   <td width="174">Staff</td>

   <td width="174">Members that teach courses at the University</td>

   <td width="174">Members</td>

   <td width="174">Staff make reservations to loan a resource</td>

  </tr>

  <tr>

   <td width="174">Acquisitions</td>

   <td width="174">Requests made by members, so they have access to new/more resources</td>

   <td width="174"> </td>

   <td width="174">Members make acquisitions which is then accepted or denied by admin staff</td>

  </tr>

  <tr>

   <td width="174">Privilege</td>

   <td width="174">Freedom to loan a resource from the School of SEEC</td>

   <td width="174"> </td>

   <td width="174">Student members have privilege which allows them to loan items</td>

  </tr>

  <tr>

   <td width="174">Administrator</td>

   <td width="174">A member of staff who decides/organizes acquisition requests</td>

   <td width="174"> </td>

   <td width="174">Checks to see if new resources can be supplied to members</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong> </strong>

<strong>RELATIONSHIP TYPES:</strong>

<table>

 <tbody>

  <tr>

   <td width="139">Entity Name</td>

   <td width="139">Multiplicity</td>

   <td width="139">Relationship</td>

   <td width="139">Multiplicity</td>

   <td width="139">Entity Name</td>

  </tr>

  <tr>

   <td width="139">Catalogue</td>

   <td width="139">1.. *</td>

   <td width="139">Has</td>

   <td width="139">*..1</td>

   <td width="139">Resources</td>

  </tr>

  <tr>

   <td width="139">Resources</td>

   <td width="139">*..*</td>

   <td width="139">Categorized</td>

   <td width="139">*..*</td>

   <td width="139">Category</td>

  </tr>

  <tr>

   <td width="139">Category</td>

   <td width="139">1..1</td>

   <td width="139">ProvidesAccessTo</td>

   <td width="139">*..1</td>

   <td width="139">Location</td>

  </tr>

  <tr>

   <td width="139">Location</td>

   <td width="139">1..*</td>

   <td width="139">Holds</td>

   <td width="139">1..1</td>

   <td width="139">Movable Resource</td>

  </tr>

  <tr>

   <td width="139">Location</td>

   <td width="139">1..*</td>

   <td width="139">Holds</td>

   <td width="139">1..1</td>

   <td width="139">Non-movable Resource</td>

  </tr>

  <tr>

   <td width="139">Resources</td>

   <td width="139">*..1</td>

   <td width="139">BelongsTo</td>

   <td width="139">1..*</td>

   <td width="139">Loan</td>

  </tr>

  <tr>

   <td width="139">Reservations</td>

   <td width="139">1..1</td>

   <td width="139">Requested</td>

   <td width="139">1..*</td>

   <td width="139">Loan</td>

  </tr>

  <tr>

   <td width="139">Members</td>

   <td width="139">1..*</td>

   <td width="139">Make</td>

   <td width="139">1..1</td>

   <td width="139">Reservations</td>

  </tr>

  <tr>

   <td width="139">Staff</td>

   <td width="139">*..*</td>

   <td width="139">Are</td>

   <td width="139">*..1</td>

   <td width="139">Members</td>

  </tr>

  <tr>

   <td width="139">Student</td>

   <td width="139">*..*</td>

   <td width="139">Are</td>

   <td width="139">*..1</td>

   <td width="139">Members</td>

  </tr>

  <tr>

   <td width="139">Members</td>

   <td width="139">0..*</td>

   <td width="139">Requests</td>

   <td width="139">1..*</td>

   <td width="139">Acquisitions</td>

  </tr>

  <tr>

   <td width="139">Administrator</td>

   <td width="139">1..*</td>

   <td width="139">Accepts/Denies</td>

   <td width="139">1..*</td>

   <td width="139">Acquisitions</td>

  </tr>

  <tr>

   <td width="139">Student</td>

   <td width="139">1..1</td>

   <td width="139">Have</td>

   <td width="139">1..*</td>

   <td width="139">Privilege</td>

  </tr>

 </tbody>

</table>

<strong>ATTRIBUTE TYPES: </strong>

<table>

 <tbody>

  <tr>

   <td width="108">Entity Name</td>

   <td width="110">Attributes</td>

   <td width="129">Description</td>

   <td width="99">Data Type &amp; Length</td>

   <td width="53">Nulls</td>

   <td width="63">Multi-valued</td>

   <td width="69">Derived</td>

   <td width="67">Default</td>

  </tr>

  <tr>

   <td rowspan="2" width="108">Catalogue</td>

   <td width="110">Physical Resources</td>

   <td width="129">Items that can be loaned physically</td>

   <td width="99">Varchar(50)</td>

   <td width="53">No</td>

   <td width="63">Yes</td>

   <td width="69">No</td>

   <td width="67">No</td>

  </tr>

  <tr>

   <td width="110">Online Resources</td>

   <td width="129">Items that can be loaned virtually</td>

   <td width="99">Varchar(50)</td>

   <td width="53">No</td>

   <td width="63">Yes</td>

   <td width="69">No</td>

   <td width="67">No</td>

  </tr>

  <tr>

   <td rowspan="3" width="108">Resources</td>

   <td width="110">Resource ID</td>

   <td width="129">ID of the resource</td>

   <td width="99">Char(10)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67">Yes</td>

  </tr>

  <tr>

   <td width="110">Description</td>

   <td width="129">Describes the resource</td>

   <td width="99">Varchar(50)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67">Yes</td>

  </tr>

  <tr>

   <td width="110">Status</td>

   <td width="129">Status of a resource being loaned</td>

   <td width="99">Varchar(30)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">Yes</td>

   <td width="67">No</td>

  </tr>

  <tr>

   <td rowspan="6" width="108">Loan</td>

   <td width="110">Offering ID</td>

   <td width="129">ID of the offering loan</td>

   <td width="99">Char(10)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67">Yes</td>

  </tr>

  <tr>

   <td width="110">Course ID</td>

   <td width="129">ID of the course</td>

   <td width="99">Char(10)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67">Yes</td>

  </tr>

  <tr>

   <td width="110">Name</td>

   <td width="129">Name of the loan</td>

   <td width="99">Varchar(30)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67">Yes</td>

  </tr>

  <tr>

   <td width="110">Semester Offered</td>

   <td width="129">Semester that the loan is offered</td>

   <td width="99">Char(1)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67">Yes</td>

  </tr>

  <tr>

   <td width="110">Year Offered</td>

   <td width="129">Year that the loan is offered</td>

   <td width="99">Char(4)</td>

   <td width="53">No</td>

   <td width="63">No</td>

   <td width="69">No</td>

   <td width="67">Yes</td>

  </tr>

  <tr>

   <td width="110">Course Beginning/End Date</td>

   <td width="129">Date of the course’s beginning/ending</td>

   <td width="99">Varchar(20)</td>

   <td width="53">No</td>

   <td width="63">Yes</td>

   <td width="69">No</td>

   <td width="67">No</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>ATTRIBUTE TYPES (CONT.): </strong>

<table>

 <tbody>

  <tr>

   <td width="87">Entity Name</td>

   <td width="87">Attributes</td>

   <td width="87">Description</td>

   <td width="87">Data Type &amp; Length</td>

   <td width="87">Nulls</td>

   <td width="87">Multi-valued</td>

   <td width="87">Derived</td>

   <td width="87">Default</td>

  </tr>

  <tr>

   <td width="87">Members</td>

   <td width="87">Member ID</td>

   <td width="87">ID of a member</td>

   <td width="87">Char(10)</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">Yes</td>

  </tr>

  <tr>

   <td width="87"> </td>

   <td width="87">Name</td>

   <td width="87">Name of member</td>

   <td width="87">Varchar(30)</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">Yes</td>

  </tr>

  <tr>

   <td width="87"> </td>

   <td width="87">Email</td>

   <td width="87">Email of member</td>

   <td width="87">Varchar(30)</td>

   <td width="87">No</td>

   <td width="87">Yes</td>

   <td width="87">No</td>

   <td width="87">No</td>

  </tr>

  <tr>

   <td width="87"> </td>

   <td width="87">Address</td>

   <td width="87">Address of member</td>

   <td width="87">Varchar(50)</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">Yes</td>

  </tr>

  <tr>

   <td width="87"> </td>

   <td width="87">Status</td>

   <td width="87">Status of member</td>

   <td width="87">Varchar(12)</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">Yes</td>

  </tr>

  <tr>

   <td width="87"> </td>

   <td width="87">Phone Number</td>

   <td width="87">Phone number(s) of member</td>

   <td width="87">Char(10)</td>

   <td width="87">No</td>

   <td width="87">Yes</td>

   <td width="87">No</td>

   <td width="87">No</td>

  </tr>

  <tr>

   <td width="87"> </td>

   <td width="87">Comments Field</td>

   <td width="87">Comments about member</td>

   <td width="87">Varchar(100)</td>

   <td width="87">Yes</td>

   <td width="87">Yes</td>

   <td width="87">No</td>

   <td width="87">No</td>

  </tr>

  <tr>

   <td width="87">Administrator</td>

   <td width="87">Status</td>

   <td width="87">Status of the acquisition</td>

   <td width="87">Varchar(15)</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">Yes</td>

  </tr>

  <tr>

   <td width="87"> </td>

   <td width="87">Fund Code</td>

   <td width="87">Code of Fund</td>

   <td width="87">Char(5)</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">Yes</td>

  </tr>

  <tr>

   <td width="87"> </td>

   <td width="87">Vendor Code</td>

   <td width="87">Code of Vendor</td>

   <td width="87">Char(5)</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">Yes</td>

  </tr>

  <tr>

   <td width="87"> </td>

   <td width="87">Price</td>

   <td width="87">How much the resource costs</td>

   <td width="87">Decimal(5)</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">Yes</td>

  </tr>

  <tr>

   <td width="87"> </td>

   <td width="87">Other Notes Pertaining to the Request</td>

   <td width="87">Extra notes about the new resource</td>

   <td width="87">Varchar(50)</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">Yes</td>

  </tr>

  <tr>

   <td width="87">Reservations</td>

   <td width="87">Pickup Date and Time</td>

   <td width="87">Date and time resources are to be given</td>

   <td width="87">Varchar(20)</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">Yes</td>

  </tr>

  <tr>

   <td width="87"> </td>

   <td width="87">Return Date and Time</td>

   <td width="87">Date and time resources are due</td>

   <td width="87">Varchar(20)</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">No</td>

   <td width="87">Yes</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>ATTRIBUTE TYPES (CONT.): </strong>

<table>

 <tbody>

  <tr>

   <td width="105">Entity Name</td>

   <td width="134">Attributes</td>

   <td width="105">Description</td>

   <td width="91">Data Type &amp; Length</td>

   <td width="57">Nulls</td>

   <td width="65">Multi-valued</td>

   <td width="71">Derived</td>

   <td width="69">Default</td>

  </tr>

  <tr>

   <td rowspan="3" width="105">Student and Staff</td>

   <td width="134">IDs</td>

   <td width="105">ID of student/staff</td>

   <td width="91">Char(10)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td width="134">Name</td>

   <td width="105">Name of student/staff</td>

   <td width="91">Varchar(30)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td width="134">Email</td>

   <td width="105">Email of student/staff</td>

   <td width="91">Varchar(30)</td>

   <td width="57">No</td>

   <td width="65">Yes</td>

   <td width="71">No</td>

   <td width="69">No</td>

  </tr>

  <tr>

   <td rowspan="4" width="105">Category</td>

   <td width="134">Category Code</td>

   <td width="105">Code of the resource’s category</td>

   <td width="91">Char(5)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td width="134">Name</td>

   <td width="105">Name of category</td>

   <td width="91">Varchar(30)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td width="134">Description</td>

   <td width="105">Description of category</td>

   <td width="91">Varchar(50)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td width="134">Max Time Allowed to Borrow/Book</td>

   <td width="105">Time a resource can be used</td>

   <td width="91">Varchar(10)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td rowspan="4" width="105">Location</td>

   <td width="134">Location ID</td>

   <td width="105">ID of location</td>

   <td width="91">Char(8)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td width="134">Room</td>

   <td width="105">Room location</td>

   <td width="91">Char(3)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td width="134">Building</td>

   <td width="105">Building location</td>

   <td width="91">Varchar(3)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td width="134">Campus</td>

   <td width="105">Campus location</td>

   <td width="91">Varchar(15)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td rowspan="6" width="105">Movable Resources</td>

   <td width="134">Name</td>

   <td width="105">Name of resource</td>

   <td width="91">Varchar(20)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td width="134">Make</td>

   <td width="105">Make of resource</td>

   <td width="91">Varchar(20)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td width="134">Manufacturer</td>

   <td width="105">Manufacturer of resource</td>

   <td width="91">Varchar(20)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td width="134">Model</td>

   <td width="105">Model of resource</td>

   <td width="91">Char(12)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td width="134">Year</td>

   <td width="105">Age of resource</td>

   <td width="91">Char(4)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

  <tr>

   <td width="134">Asset Value</td>

   <td width="105">Value of resource</td>

   <td width="91">Decimal(5)</td>

   <td width="57">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="69">Yes</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>ATTRIBUTE TYPES (CONT.): </strong>

<table>

 <tbody>

  <tr>

   <td width="105">Entity Name</td>

   <td width="134">Attributes</td>

   <td width="105">Description</td>

   <td width="93">Data Type &amp; Length</td>

   <td width="56">Nulls</td>

   <td width="65">Multi-valued</td>

   <td width="71">Derived</td>

   <td width="68">Default</td>

  </tr>

  <tr>

   <td rowspan="4" width="105">Non-movable resources</td>

   <td width="134">Maximum Room Capacity</td>

   <td width="105">How many people can fit in a room</td>

   <td width="93">Varchar(30)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68">Yes</td>

  </tr>

  <tr>

   <td width="134">Room Name</td>

   <td width="105">Name of Room</td>

   <td width="93">Char(3)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68">Yes</td>

  </tr>

  <tr>

   <td width="134">Building</td>

   <td width="105">Building location</td>

   <td width="93">Varchar(3)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68">Yes</td>

  </tr>

  <tr>

   <td width="134">Campus</td>

   <td width="105">Campus location</td>

   <td width="93">Varchar(15)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68">Yes</td>

  </tr>

  <tr>

   <td rowspan="4" width="105">Privilege</td>

   <td width="134">Name</td>

   <td width="105">Name of privilege</td>

   <td width="93">Varchar(30)</td>

   <td width="56">No</td>

   <td width="65">Yes</td>

   <td width="71">No</td>

   <td width="68">No</td>

  </tr>

  <tr>

   <td width="134">Description</td>

   <td width="105">Description of privilege</td>

   <td width="93">Varchar(50)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68">Yes</td>

  </tr>

  <tr>

   <td width="134">Privilege Category</td>

   <td width="105">What kind of privilege a student member has</td>

   <td width="93">Varchar(16)</td>

   <td width="56">No</td>

   <td width="65">Yes</td>

   <td width="71">No</td>

   <td width="68">Yes</td>

  </tr>

  <tr>

   <td width="134">Maximum Number of Resources allowed to be Booked/Borrowed</td>

   <td width="105">Time allowed for a student to borrow/book a resource</td>

   <td width="93">Varchar(10)</td>

   <td width="56">No</td>

   <td width="65">Yes</td>

   <td width="71">No</td>

   <td width="68">No</td>

  </tr>

  <tr>

   <td rowspan="8" width="105">Acquisitions</td>

   <td width="134">Person Requesting Acquisition</td>

   <td width="105">Name of person</td>

   <td width="93">Varchar(30)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68">Yes</td>

  </tr>

  <tr>

   <td width="134">Item Name</td>

   <td width="105">Name of item</td>

   <td width="93">Varchar(30)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68">Yes</td>

  </tr>

  <tr>

   <td width="134">Make</td>

   <td width="105">Make of resource</td>

   <td width="93">Varchar(20)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68">Yes</td>

  </tr>

  <tr>

   <td width="134">Manufacturer</td>

   <td width="105">Manufacturer of resource</td>

   <td width="93">Varchar(20)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68">Yes</td>

  </tr>

  <tr>

   <td width="134">Model</td>

   <td width="105">Model of resource</td>

   <td width="93">Char(12)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68">Yes</td>

  </tr>

  <tr>

   <td width="134">Year</td>

   <td width="105">Age of resource</td>

   <td width="93">Char(4)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68">Yes</td>

  </tr>

  <tr>

   <td width="134">Description of Required Item</td>

   <td width="105">Item description</td>

   <td width="93">Varchar(50)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">No</td>

   <td width="68">Yes</td>

  </tr>

  <tr>

   <td width="134">Item Urgency</td>

   <td width="105">How much is the item needed</td>

   <td width="93">Varchar(10)</td>

   <td width="56">No</td>

   <td width="65">No</td>

   <td width="71">Yes</td>

   <td width="68">No</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong> </strong>