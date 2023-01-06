##

Privileged Identity Management (PIM) is a service in Azure Active Directory (Azure AD) that enables you to manage, control, and monitor `_____` to important resources in your organization. These resources include resources in Azure AD, Azure, and other Microsoft Online Services such as Microsoft 365 or Microsoft Intune.

%

Privileged Identity Management (PIM) is a service in Azure Active Directory (Azure AD) that enables you to manage, control, and monitor **access** to important resources in your organization. These resources include resources in Azure AD, Azure, and other Microsoft Online Services such as Microsoft 365 or Microsoft Intune.

##

Organizations want to minimize the number of people who have access to secure information or resources, because that reduces the chance of

- a malicious actor getting access
- an authorized user inadvertently impacting a sensitive resource

However, users still need to carry out privileged operations in Azure AD, Azure, Microsoft 365, or SaaS apps. Organizations can give users `_____` privileged access to Azure and Azure AD resources and can oversee what those users are doing with their privileged access.

%

However, users still need to carry out privileged operations in Azure AD, Azure, Microsoft 365, or SaaS apps. Organizations can give users **just-in-time** privileged access to Azure and Azure AD resources and can oversee what those users are doing with their privileged access.

##

Using Privileged Identity Management (PIM) requires Azure AD `_____` licenses.

%

Using Privileged Identity Management (PIM) requires Azure AD **Premium P2** licenses.

##

Privileged Identity Management provides `_____`-based and `_____`-based role activation to mitigate the risks of excessive, unnecessary, or misused access permissions on resources that you care about.

%

Privileged Identity Management provides **time**-based and **approval**-based role activation to mitigate the risks of excessive, unnecessary, or misused access permissions on resources that you care about.

##

Some of the key features of Privileged Identity Management:

- Provide `_____` privileged access to Azure AD and Azure resources
- Assign `_____` access to resources using start and end dates
- Require `_____` to activate privileged roles
- Enforce `_____` to activate any role
- Use `_____` to understand why users activate
- Get `_____` when privileged roles are activated
- Conduct `_____` to ensure users still need roles
- Download `_____` for internal or external audit
- Prevents removal of the `_____` and `_____` role assignments

%

- Provide **just-in-time** privileged access to Azure AD and Azure resources
- Assign **time-bound** access to resources using start and end dates
- Require **approval** to activate privileged roles
- Enforce **multi-factor authentication** to activate any role
- Use **justification** to understand why users activate
- Get **notifications** when privileged roles are activated
- Conduct **access reviews** to ensure users still need roles
- Download **audit history** for internal or external audit
- Prevents removal of the **last active Global Administrator** and **Privileged Role Administrator** role assignments

##

Once you set up Privileged Identity Management, you'll see `Tasks`, `Manage`, and `Activity` options in the `_____` menu. As an administrator, you'll choose between options such as managing `Azure AD roles`, managing `Azure resource` roles, or privileged access groups. When you choose what you want to manage, you see the appropriate set of options for that option.

%

Once you set up Privileged Identity Management, you'll see `Tasks`, `Manage`, and `Activity` options in the **left navigation** menu. As an administrator, you'll choose between options such as managing `Azure AD roles`, managing `Azure resource` roles, or privileged access groups. When you choose what you want to manage, you see the appropriate set of options for that option.

##

For Azure AD roles in Privileged Identity Management, only a user who is in the `Privileged Role Administrator` or `Global Administrator` role can manage `_____` for other administrators. `Global Administrator`s, `Security Administrator`s, `Global Reader`s, and `Security Reader`s can also view `_____` to Azure AD roles in Privileged Identity Management.

%

For Azure AD roles in Privileged Identity Management, only a user who is in the `Privileged Role Administrator` or `Global Administrator` role can manage **assignments** for other administrators. `Global Administrator`s, `Security Administrator`s, `Global Reader`s, and `Security Reader`s can also view **assignments** to Azure AD roles in Privileged Identity Management.

##

For Azure resource roles in Privileged Identity Management, only a subscription administrator, a resource Owner, or a resource User Access administrator can manage `_____` for other administrators. Users who are `Privileged Role Administrator`s, `Security Administrator`s, or `Security Reader`s don't by default have access to view `_____` to Azure resource roles in Privileged Identity Management.

%

For Azure resource roles in Privileged Identity Management, only a subscription administrator, a resource Owner, or a resource User Access administrator can manage **assignments** for other administrators. Users who are `Privileged Role Administrator`s, `Security Administrator`s, or `Security Reader`s don't by default have access to view **assignments** to Azure resource roles in Privileged Identity Management.

##

In PIM, the `_____` role assignment category type is a role assignment that requires a user to perform one or more actions to use the role. If a user has been made eligible for a role, that means they can activate the role when they need to perform privileged tasks. There's no difference in the access given to someone with a permanent versus an eligible role assignment. The only difference is that some people don't need that access all the time.

%

In PIM, the **eligible** role assignment category type is a role assignment that requires a user to perform one or more actions to use the role. If a user has been made eligible for a role, that means they can activate the role when they need to perform privileged tasks. There's no difference in the access given to someone with a permanent versus an eligible role assignment. The only difference is that some people don't need that access all the time.

##

In PIM, the `_____` role assignment category type is a role assignment that doesn't require a user to perform any action to use the role. Users assigned as active have the privileges assigned to the role.

%

In PIM, the **active** role assignment category type is a role assignment that doesn't require a user to perform any action to use the role. Users assigned as active have the privileges assigned to the role.

##

In PIM, `_____` means the process of performing one or more actions to use a role that a user is eligible for. Actions might include performing a multi-factor authentication (MFA) check, providing a business justification, or requesting approval from designated approvers.

%

In PIM, **activate** means the process of performing one or more actions to use a role that a user is eligible for. Actions might include performing a multi-factor authentication (MFA) check, providing a business justification, or requesting approval from designated approvers.

##

In PIM, the `_____` role assignment category state is a user that has an active role assignment.

%

In PIM, the **assigned** role assignment category state is a user that has an active role assignment.

##

In PIM, the `_____` role assignment category state is a user that has an eligible role assignment, performed the actions to activate the role, and is now active. Once activated, the user can use the role for a pre-configured period of time before they need to activate again.

%

In PIM, the **activated** role assignment category state is a user that has an eligible role assignment, performed the actions to activate the role, and is now active. Once activated, the user can use the role for a pre-configured period of time before they need to activate again.

##

In PIM, the `_____` role assignment category duration is a role assignment where a user is always eligible to activate the role.

%

In PIM, the **permanent eligible** role assignment category duration is a role assignment where a user is always eligible to activate the role.

##

In PIM, the `_____` role assignment category duration is a role assignment where a user can always use the role without performing any actions.

%

In PIM, the **permanent active** role assignment category duration is a role assignment where a user can always use the role without performing any actions.

##

In PIM, the `_____` role assignment category duration is a role assignment where a user is eligible to activate the role only within start and end dates.

%

In PIM, the **time-bound eligible** role assignment category duration is a role assignment where a user is eligible to activate the role only within start and end dates.

##

In PIM, the `_____` role assignment category duration is a role assignment where a user can use the role only within start and end dates.

%

In PIM, the **time-bound active** role assignment category duration is a role assignment where a user can use the role only within start and end dates.

##

`_____` access is a model in which users receive temporary permissions to perform privileged tasks, which prevents malicious or unauthorized users from gaining access after the permissions have expired. Access is granted only when users need it.

%

**just-in-time (JIT)** access is a model in which users receive temporary permissions to perform privileged tasks, which prevents malicious or unauthorized users from gaining access after the permissions have expired. Access is granted only when users need it.

##

Principle of `_____` access is a recommended security practice in which every user is provided with only the minimum privileges needed to accomplish the tasks they're authorized to perform. This practice minimizes the number of Global Administrators and instead uses specific administrator roles for certain scenarios.

%

Principle of **least privilege** access is a recommended security practice in which every user is provided with only the minimum privileges needed to accomplish the tasks they're authorized to perform. This practice minimizes the number of Global Administrators and instead uses specific administrator roles for certain scenarios.

##

The PIM role assignments give you a secure way to grant access to resources in your 

%

organization

##

In PIM, the assignment process includes

- assign `_____` to members
- activate `_____`
- approve or deny `_____`
- extend and renew `_____`

%

- assign **roles** to members
- activate **assignments**
- approve or deny **requests**
- extend and renew **assignments**

##

PIM keeps you informed by sending you and other participants `_____` notifications. These `_____`s might also include links to relevant tasks, such activating, approve or deny a request.

%

PIM keeps you informed by sending you and other participants **email** notifications. These **email**s might also include links to relevant tasks, such activating, approve or deny a request.

##

The assignment process starts by assigning `_____` to members. To grant access to a resource, the administrator assigns `_____` to users, groups, service principals, or managed identities.

%

The assignment process starts by assigning **roles** to members. To grant access to a resource, the administrator assigns **roles** to users, groups, service principals, or managed identities.

##

In PIM, an assignment includes the following data:

- The members or owners to assign the `_____`.
- The `_____` of the assignment. The `_____` limits the assigned role to a particular set of resources.
- The `_____` of the assignment
  - Eligible assignments require the member of the role to perform an `_____` to use the role. `_____`s might include activation, or requesting approval from designated approvers.
  - `_____` assignments don't require the member to perform any action to use the role. Members assigned as `_____` have the privileges assigned to the role.
- The `_____` of the assignment, using start and end dates or permanent. For eligible assignments, the members can activate or requesting approval during the start and end dates. For active assignments, the members can use the assign role during this period of time.

%

- The members or owners to assign the **role**.
- The **scope** of the assignment. The **scope** limits the assigned role to a particular set of resources.
- The **type** of the assignment
  - Eligible assignments require the member of the role to perform an **action** to use the role. **Action**s might include activation, or requesting approval from designated approvers.
  - **Active** assignments don't require the member to perform any action to use the role. Members assigned as **active** have the privileges assigned to the role.
- The **duration** of the assignment, using start and end dates or permanent. For eligible assignments, the members can activate or requesting approval during the start and end dates. For active assignments, the members can use the assign role during this period of time.

##

If users have been made eligible for a role, then they must `_____` the role assignment before using the role. To `_____` the role, users select specific `_____` duration within the maximum (configured by administrators), and the reason for the `_____` request.

%

If users have been made eligible for a role, then they must **activate** the role assignment before using the role. To **activate** the role, users select specific **activation** duration within the maximum (configured by administrators), and the reason for the **activation** request.

##

If the role requires approval to activate, a `_____` will appear in the upper right corner of the user's browser informing them the request is pending approval. If an approval isn't required, the member can start using the role.

%

If the role requires approval to activate, a **notification** will appear in the upper right corner of the user's browser informing them the request is pending approval. If an approval isn't required, the member can start using the role.

##

Delegated `_____` receive email notifications when a role request is pending their approval. `_____` can view, `_____` or deny these pending requests in PIM. After the request has been `_____`, the member can start using the role. For example, if a user or a group was assigned with Contribution role to a resource group, they'll be able to manage that particular resource group.

%

Delegated **approvers** receive email notifications when a role request is pending their approval. **Approvers** can view, **approve** or deny these pending requests in PIM. After the request has been **approved**, the member can start using the role. For example, if a user or a group was assigned with Contribution role to a resource group, they'll be able to manage that particular resource group.

##

After administrators set up time-bound owner or member assignments, the first question you might ask is what happens if an assignment expires? In this new version, we provide two options for this scenario:

- `_____` – When a role assignment nears expiration, the user can use Privileged Identity Management to request an `_____` for the role assignment
- `_____` – When a role assignment has already expired, the user can use Privileged Identity Management to request a `_____` for the role assignment

Both user-initiated actions require an approval from a Global Administrator or Privileged Role Administrator. Admins don't need to be in the business of managing assignment expirations. You can just wait for the `_____` or `_____` requests to arrive for simple approval or denial.

%

After administrators set up time-bound owner or member assignments, the first question you might ask is what happens if an assignment expires? In this new version, we provide two options for this scenario:

- **Extend** – When a role assignment nears expiration, the user can use Privileged Identity Management to request an **extension** for the role assignment
- **Renew** – When a role assignment has already expired, the user can use Privileged Identity Management to request a **renewal** for the role assignment

Both user-initiated actions require an approval from a Global Administrator or Privileged Role Administrator. Admins don't need to be in the business of managing assignment expirations. You can just wait for the **extension** or **renewal** requests to arrive for simple approval or denial.

##

Privileged Identity Management supports the following scenarios:

- `_____` permissions
  - Enable approval for specific roles
  - Specify approver users or groups to approve requests
  - View request and approval history for all privileged roles
- `_____` permissions
  - View pending approvals (requests)
  - Approve or reject requests for role elevation (single and bulk)
  - Provide justification for my approval or rejection
- `_____` permissions
  - Request activation of a role that requires approval
  - View the status of your request to activate
  - Complete your task in Azure AD if activation was approved

  %

- **Privileged Role Administrator** permissions
  - Enable approval for specific roles
  - Specify approver users or groups to approve requests
  - View request and approval history for all privileged roles
- **Approver** permissions
  - View pending approvals (requests)
  - Approve or reject requests for role elevation (single and bulk)
  - Provide justification for my approval or rejection
- **Eligible role user** permissions
  - Request activation of a role that requires approval
  - View the status of your request to activate
  - Complete your task in Azure AD if activation was approved

##

In Privileged Identity Management (PIM), you can now assign eligibility for membership or ownership of privileged access `_____`. Starting with this preview, you can assign Azure Active Directory (Azure AD) built-in roles to cloud `_____` and use PIM to manage group member and owner eligibility and activation

%

In Privileged Identity Management (PIM), you can now assign eligibility for membership or ownership of privileged access **groups**. Starting with this preview, you can assign Azure Active Directory (Azure AD) built-in roles to cloud **groups** and use PIM to manage group member and owner eligibility and activation

##

To assign a privileged access group to a role for administrative access to `_____`, `_____`, or `_____`, use the Azure AD portal Roles and Administrators experience and not in the Privileged Access Groups experience to make the user or group eligible for activation into the group.

%

To assign a privileged access group to a role for administrative access to **Exchange**, **Security & Compliance Center**, or **SharePoint**, use the Azure AD portal Roles and Administrators experience and not in the Privileged Access Groups experience to make the user or group eligible for activation into the group.

##

Different just-in-time policies for each group
Some organizations use tools like Azure AD business-to-business (B2B) collaboration to invite their partners as guests to their Azure AD organization. Instead of a single just-in-time policy for all assignments to a privileged role, you can create two different `_____` with their own policies. You can enforce less strict requirements for your trusted employees, and stricter requirements like approval workflow for your partners when they request activation into their assigned group.

%

Different just-in-time policies for each group
Some organizations use tools like Azure AD business-to-business (B2B) collaboration to invite their partners as guests to their Azure AD organization. Instead of a single just-in-time policy for all assignments to a privileged role, you can create two different **privileged access groups** with their own policies. You can enforce less strict requirements for your trusted employees, and stricter requirements like approval workflow for your partners when they request activation into their assigned group.

##

With the privileged access groups preview, you can give workload-specific administrators quick access to multiple `_____` with a single just-in-time request. For example, your Tier 3 Office Admins might need just-in-time access to the Exchange Admin, Office Apps Admin, Teams Admin, and Search Admin roles to thoroughly investigate incidents daily. Before today it would require four consecutive requests, which are a process that takes some time. Instead, you can create a role assignable group called “Tier 3 Office Admins”, assign it to each of the four roles previously mentioned (or any Azure AD built-in roles) and enable it for Privileged Access in the group’s Activity section. Once enabled for privileged access, you can configure the just-in-time settings for members of the group and assign your admins and owners as eligible. When the admins elevate into the group, they’ll become members of all four Azure AD roles.

%

With the privileged access groups preview, you can give workload-specific administrators quick access to multiple **roles** with a single just-in-time request. For example, your Tier 3 Office Admins might need just-in-time access to the Exchange Admin, Office Apps Admin, Teams Admin, and Search Admin roles to thoroughly investigate incidents daily. Before today it would require four consecutive requests, which are a process that takes some time. Instead, you can create a role assignable group called “Tier 3 Office Admins”, assign it to each of the four roles previously mentioned (or any Azure AD built-in roles) and enable it for Privileged Access in the group’s Activity section. Once enabled for privileged access, you can configure the just-in-time settings for members of the group and assign your admins and owners as eligible. When the admins elevate into the group, they’ll become members of all four Azure AD roles.

##

Azure Active Directory (Azure AD) `_____` users are part of the business-to-business (B2B) collaboration capabilities within Azure AD so that you can manage external `_____` users and vendors as `_____`s in Azure AD. For example, you can use these Privileged Identity Management features for Azure identity tasks with `_____`s such as assigning access to specific Azure resources, specifying assignment duration and end date, or requiring two-step verification on active assignment or activation.

%

Azure Active Directory (Azure AD) **guest** users are part of the business-to-business (B2B) collaboration capabilities within Azure AD so that you can manage external **guest** users and vendors as **guest**s in Azure AD. For example, you can use these Privileged Identity Management features for Azure identity tasks with **guest**s such as assigning access to specific Azure resources, specifying assignment duration and end date, or requiring two-step verification on active assignment or activation.

##

Examples of when you might invite guests to your organization:

- Allow an external `_____`-employed vendor that only has an email account to access your Azure resources for a project.
- Allow an external partner in a `_____` organization that uses on-premises Active Directory Federation Services to access your expense application.
- Allow support engineers not in your `_____` (such as Microsoft support) to temporarily access your Azure resource to troubleshoot issues.

%

- Allow an external **self**-employed vendor that only has an email account to access your Azure resources for a project.
- Allow an external partner in a **large** organization that uses on-premises Active Directory Federation Services to access your expense application.
- Allow support engineers not in your **organization** (such as Microsoft support) to temporarily access your Azure resource to troubleshoot issues.

##

When you use B2B collaboration, you can invite an external user to your organization as a `_____`. The `_____` can be managed as a user in your organization, but a `_____` has to be authenticated in their home organization and not in your Azure AD organization. This means that if the `_____` no longer has access to their home organization, they also lose access to your organization. For example, if the `_____` leaves their organization, they automatically lose access to any resources you shared with them in Azure AD without you having to do anything.

%

When you use B2B collaboration, you can invite an external user to your organization as a **guest**. The **guest** can be managed as a user in your organization, but a **guest** has to be authenticated in their home organization and not in your Azure AD organization. This means that if the **guest** no longer has access to their home organization, they also lose access to your organization. For example, if the **guest** leaves their organization, they automatically lose access to any resources you shared with them in Azure AD without you having to do anything.
