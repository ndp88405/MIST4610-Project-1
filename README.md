# MIST4610-Project-1
MIST 4610 - Project 1 
<h1>TEAM MEMBERS (21484_G6)</h1>
<li>Ademoye, Adekanle <a href="url">link for github</a></li>
<li>Keenan, Patrick <a href="url">link for github</a></li>
<li>Patel, Kishan <a href="url">link for github</a></li>
<li>Thomas, Reuben <a href="url">link for github</a></li>
<li>Patel, Nidhi <a href="https://github.com/ndp88405">ndp88405</a></li>

<h1>Problem Description</h1>
<p>A description of the scenario that you are modeling describing it in sufficient detail that makes
sense in the context of your data model. This should be reflective of your conversation with your
group and instructor (if you reach out for help).</p>

<h1>Data Model</h1>
<p>Our data model is based on a hypothetical Football League based in Georgia. It captures key aspects of team organization, player management, staff roles, sponsorships, and league affiliations. 

At its core, the <b> Player</b> table holds detailed information about the individual athletes, like their physical attributes, position, and team affiliation. Each player is linked to a specific <b>Position</b>, which defines their roles on the field. The positions include quarterback, wide receiver, offensive lineman, defensive lineman, safety, and cornerback. The players’ contract details are stored in the <b>Contracts</b> table, which tracks their salary, start and end dates of the contract. 

Players belong to a <b>Team </b>, which is identified by the name, city and their associate home venue, which is stored in the <b>Venue</b> table, which also records the stadium capacity. Since there are 10 teams in the league we needed to make sure we had additional organizational elements which included, sponsorship agreements captured in the <b>Sponsor</b> table, which details sponsoring companies and the type of sponsor the company is, like Beverage, Airlines, or Transportation. 

The <b> Coach </b> table links specific coaches to teams, while the <b> Staff </b> table holds information on other essential personnel, such as medical staff. The <b>team_Staff</b> table facilitates a many-to-many relationship between teams and their staff members. Teams also have designated uniforms, recorded in the <b>Uniform</b> table, which captures uniform colors, patterns, and materials. 

Beyond individual teams, the model accounts for league structures through the <b>Conference</b> table, which categorizes teams based on geographical location, East or West. The <b>teamConference</b> table establishes a many-to-many relationship between teams and conferences, enabling teams to participate in multiple league structures. 

</p>
<img alt="Data Model" src="https://github.com/user-attachments/assets/1758a320-708e-4a1e-868f-c8baf724b529"/>



<h1>Data Dictionary</h1>
<img width="630" alt="Player" src="https://github.com/user-attachments/assets/cd33ce3d-1ffd-4493-85dd-b79ddc3c1d6c" />
<img width="630" alt="team_Staff" src="https://github.com/user-attachments/assets/75bb0d68-c446-4044-bc38-0e8515f84738" />
<img width="629" alt="Staff" src="https://github.com/user-attachments/assets/e075acbe-8154-4e6a-9a53-c8514f21e7b3" />
<img width="629" alt="Uniform" src="https://github.com/user-attachments/assets/a6257ac0-3062-46e5-bbb3-34be07f26a2f" />
<img width="629" alt="Positions" src="https://github.com/user-attachments/assets/3a027fd8-c28c-462e-970f-91c6309c5a39" />
<img width="629" alt="Venue" src="https://github.com/user-attachments/assets/36b0de15-75a9-47d5-86a3-fbf22a6a8ab9" />
<img width="629" alt="Sponsor" src="https://github.com/user-attachments/assets/d941eaf7-2e33-49ef-8568-c589bc5c848c" />
<img width="629" alt="Contracts" src="https://github.com/user-attachments/assets/4770d067-086f-4b5c-b168-6143585f7f8c" />
<img width="629" alt="team_Conference" src="https://github.com/user-attachments/assets/6539e820-d47b-4033-84d0-57466212b07a" />
<img width="629" alt="Conference" src="https://github.com/user-attachments/assets/f066e66a-d912-4738-8f99-da102ce8b6b9" />

<h1>Queries</h1>
<h3>Query 1</h3>
<img width="629"src="https://github.com/user-attachments/assets/4a52c5db-9e9f-41f2-9254-0045b34af652"/>
<h3>Query 2</h3>
<img width="629" src="https://github.com/user-attachments/assets/5b573fc5-6cee-43c1-bd03-b00adb96dc6c"/>
<h3>Query 3</h3>
<img width="629" src ="https://github.com/user-attachments/assets/4418a27b-9a48-4859-aea8-f84b565248a2"/>
<h3>Query 4</h3>
<img width="629" src ="https://github.com/user-attachments/assets/5f4fcf98-22b7-4730-8437-4534adc0af6f"/>
<h3>Query 5</h3>
<img width="629" src ="https://github.com/user-attachments/assets/03056969-21ad-402a-8394-7e4562afa11f">

<h3>Query 6</h3>

<h3>Query 7</h3>

<h3>Query 8</h3>

<h3>Query 9</h3>

<h3>Query 10</h3>

