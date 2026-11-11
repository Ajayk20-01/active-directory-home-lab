# Active Directory Group Management

## 1. Project Overview

This exercise demonstrates how to create and manage security groups in Active Directory using Active Directory Users and Computers (ADUC) on Windows Server 2022.

Security groups help administrators manage permissions and access to organizational resources efficiently.

## 2. Lab Environment

| Component | Details |
|---|---|
| Virtualization | VMware Workstation |
| Operating System | Windows Server 2022 |
| Directory Service | Active Directory Domain Services |
| Management Tool | Active Directory Users and Computers |
| Organizational Unit | IT-Department |

## 3. Scenario

The IT department needs to organize its support team members into a security group to simplify access management.

The IT Support Engineer creates a security group and adds the appropriate user accounts.

## 4. Practical Tasks

### Task 1: Create a Security Group

1. Open Server Manager.
2. Navigate to Tools → Active Directory Users and Computers.
3. Expand the domain.
4. Open the IT-Department Organizational Unit.
5. Right-click the OU.
6. Select New → Group.
7. Enter the group name: IT-Support-Team.
8. Select Global as the group scope.
9. Select Security as the group type.
10. Click OK.

### Task 2: Add a User to the Group

1. Open the IT-Support-Team group properties.
2. Navigate to the Members tab.
3. Click Add.
4. Enter the test user's account name.
5. Click Check Names.
6. Confirm the user selection.
7. Click Apply and OK.

### Task 3: Verify Group Membership

1. Open the group properties.
2. Navigate to the Members tab.
3. Verify that the test user appears in the membership list.

## 5. Expected Result

The IT-Support-Team security group should be created successfully, and the selected test user should appear as a member.

## 6. IT Support Best Practices

- Follow the principle of least privilege.
- Add users only to authorized groups.
- Obtain approval before changing access permissions.
- Review group memberships periodically.
- Avoid unnecessary administrator privileges.
- Document all access changes in the service desk ticket.

## 7. Skills Practiced

- Active Directory Group Management
- Security Group Creation
- User Membership Management
- Identity and Access Management
- Windows Server 2022 Administration
- IT Support Access Management

## 8. Learning Outcome

Learned how to create Active Directory security groups, add user accounts, and verify group membership.

## 9. Screenshots

Screenshots from the VMware home lab will be uploaded after completing the practical exercises.

## Author

**Ajay Kammari**

IT Support | Service Desk | Windows Server | Active Directory

GitHub: https://github.com/Ajayk20-01

---

**Lab Status:** Documentation prepared. Practical results to be verified.
