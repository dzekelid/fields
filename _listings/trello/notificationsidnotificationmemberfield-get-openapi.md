---
swagger: "2.0"
x-collection-name: Trello
x-complete: 0
info:
  title: Trello Get Notifications Notification Member Field
  description: Get notifications notification member field.
  termsOfService: https://trello.com/legal
  contact:
    name: Trello
    url: https://trello.com/home
  version: "1.0"
host: trello.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /actions/{idAction}/board/{field}:
    get:
      summary: Get Actions Board Field
      description: Get actions board field.
      operationId: getActionsBoardByIdActionByField
      x-api-path-slug: actionsidactionboardfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idAction
        description: idAction
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Actions
      - Board
      - Field
  /actions/{idAction}/card/{field}:
    get:
      summary: Get Actions Card Field
      description: Get actions card field.
      operationId: getActionsCardByIdActionByField
      x-api-path-slug: actionsidactioncardfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idAction
        description: idAction
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Actions
      - Card
      - Field
  /actions/{idAction}/list/{field}:
    get:
      summary: Get Actions List Field
      description: Get actions list field.
      operationId: getActionsListByIdActionByField
      x-api-path-slug: actionsidactionlistfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idAction
        description: idAction
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Actions
      - List
      - Field
  /actions/{idAction}/member/{field}:
    get:
      summary: Get Actions Member Field
      description: Get actions member field.
      operationId: getActionsMemberByIdActionByField
      x-api-path-slug: actionsidactionmemberfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idAction
        description: idAction
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Actions
      - Member
      - Field
  /actions/{idAction}/memberCreator/{field}:
    get:
      summary: Get Actions Member Creator Field
      description: Get actions member creator field.
      operationId: getActionsMemberCreatorByIdActionByField
      x-api-path-slug: actionsidactionmembercreatorfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idAction
        description: idAction
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Actions
      - Member
      - Creator
      - Field
  /actions/{idAction}/organization/{field}:
    get:
      summary: Get Actions Organization Field
      description: Get actions organization field.
      operationId: getActionsOrganizationByIdActionByField
      x-api-path-slug: actionsidactionorganizationfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idAction
        description: idAction
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Actions
      - Organization
      - Field
  /actions/{idAction}/{field}:
    get:
      summary: Get Actions Field
      description: Get actions field.
      operationId: getActionsByIdActionByField
      x-api-path-slug: actionsidactionfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idAction
        description: idAction
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Actions
      - Field
  /boards/{idBoard}/membersInvited/{field}:
    get:
      summary: Get Boards Membersinvited Field
      description: Get boards membersinvited field.
      operationId: getBoardsMembersInvitedByIdBoardByField
      x-api-path-slug: boardsidboardmembersinvitedfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - Membersinvited
      - Field
  /boards/{idBoard}/organization/{field}:
    get:
      summary: Get Boards Organization Field
      description: Get boards organization field.
      operationId: getBoardsOrganizationByIdBoardByField
      x-api-path-slug: boardsidboardorganizationfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - Organization
      - Field
  /boards/{idBoard}/{field}:
    get:
      summary: Get Boards Field
      description: Get boards field.
      operationId: getBoardsByIdBoardByField
      x-api-path-slug: boardsidboardfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - Field
  /cards/{idCard}/board/{field}:
    get:
      summary: Get Cards Board Field
      description: Get cards board field.
      operationId: getCardsBoardByIdCardByField
      x-api-path-slug: cardsidcardboardfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idCard
        description: card id or shortlink
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Cards
      - Board
      - Field
  /cards/{idCard}/list/{field}:
    get:
      summary: Get Cards List Field
      description: Get cards list field.
      operationId: getCardsListByIdCardByField
      x-api-path-slug: cardsidcardlistfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idCard
        description: card id or shortlink
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Cards
      - List
      - Field
  /cards/{idCard}/{field}:
    get:
      summary: Get Cards Field
      description: Get cards field.
      operationId: getCardsByIdCardByField
      x-api-path-slug: cardsidcardfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idCard
        description: card id or shortlink
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Cards
      - Field
  /checklists/{idChecklist}/board/{field}:
    get:
      summary: Get Checklists Board Field
      description: Get checklists board field.
      operationId: getChecklistsBoardByIdChecklistByField
      x-api-path-slug: checklistsidchecklistboardfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idChecklist
        description: idChecklist
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Checklists
      - Board
      - Field
  /checklists/{idChecklist}/{field}:
    get:
      summary: Get Checklists Field
      description: Get checklists field.
      operationId: getChecklistsByIdChecklistByField
      x-api-path-slug: checklistsidchecklistfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idChecklist
        description: idChecklist
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Checklists
      - Field
  /labels/{idLabel}/board/{field}:
    get:
      summary: Get Labels Label Board Field
      description: Get labels label board field.
      operationId: getLabelsBoardByIdLabelByField
      x-api-path-slug: labelsidlabelboardfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idLabel
        description: idLabel
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Labels
      - Label
      - Board
      - Field
  /lists/{idList}/board/{field}:
    get:
      summary: Get Lists List Board Field
      description: Get lists list board field.
      operationId: getListsBoardByIdListByField
      x-api-path-slug: listsidlistboardfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idList
        description: idList
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Lists
      - List
      - Board
      - Field
  /lists/{idList}/{field}:
    get:
      summary: Get Lists List Field
      description: Get lists list field.
      operationId: getListsByIdListByField
      x-api-path-slug: listsidlistfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idList
        description: idList
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Lists
      - List
      - Field
  /members/{idMember}/boardsInvited/{field}:
    get:
      summary: Get Members Boardsinvited Field
      description: Get members boardsinvited field.
      operationId: getMembersBoardsInvitedByIdMemberByField
      x-api-path-slug: membersidmemberboardsinvitedfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idMember
        description: idMember or username
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Members
      - Boardsinvited
      - Field
  /members/{idMember}/organizationsInvited/{field}:
    get:
      summary: Get Members Organizationsinvited Field
      description: Get members organizationsinvited field.
      operationId: getMembersOrganizationsInvitedByIdMemberByField
      x-api-path-slug: membersidmemberorganizationsinvitedfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idMember
        description: idMember or username
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Members
      - Organizationsinvited
      - Field
  /members/{idMember}/{field}:
    get:
      summary: Get Members Field
      description: Get members field.
      operationId: getMembersByIdMemberByField
      x-api-path-slug: membersidmemberfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idMember
        description: idMember or username
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Members
      - Field
  /notifications/{idNotification}/board/{field}:
    get:
      summary: Get Notifications Notification Board Field
      description: Get notifications notification board field.
      operationId: getNotificationsBoardByIdNotificationByField
      x-api-path-slug: notificationsidnotificationboardfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idNotification
        description: idNotification
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Notifications
      - Notification
      - Board
      - Field
  /notifications/{idNotification}/card/{field}:
    get:
      summary: Get Notifications Notification Card Field
      description: Get notifications notification card field.
      operationId: getNotificationsCardByIdNotificationByField
      x-api-path-slug: notificationsidnotificationcardfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idNotification
        description: idNotification
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Notifications
      - Notification
      - Card
      - Field
  /notifications/{idNotification}/list/{field}:
    get:
      summary: Get Notifications Notification List Field
      description: Get notifications notification list field.
      operationId: getNotificationsListByIdNotificationByField
      x-api-path-slug: notificationsidnotificationlistfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idNotification
        description: idNotification
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Notifications
      - Notification
      - List
      - Field
  /notifications/{idNotification}/member/{field}:
    get:
      summary: Get Notifications Notification Member Field
      description: Get notifications notification member field.
      operationId: getNotificationsMemberByIdNotificationByField
      x-api-path-slug: notificationsidnotificationmemberfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idNotification
        description: idNotification
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Notifications
      - Notification
      - Member
      - Field
  /notifications/{idNotification}/memberCreator/{field}:
    get:
      summary: Get Notifications Notification Member Creator Field
      description: Get notifications notification member creator field.
      operationId: getNotificationsMemberCreatorByIdNotificationByField
      x-api-path-slug: notificationsidnotificationmembercreatorfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idNotification
        description: idNotification
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Notifications
      - Notification
      - Member
      - Creator
      - Field
  /notifications/{idNotification}/organization/{field}:
    get:
      summary: Get Notifications Notification Organization Field
      description: Get notifications notification organization field.
      operationId: getNotificationsOrganizationByIdNotificationByField
      x-api-path-slug: notificationsidnotificationorganizationfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idNotification
        description: idNotification
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Notifications
      - Notification
      - Organization
      - Field
  /notifications/{idNotification}/{field}:
    get:
      summary: Get Notifications Notification Field
      description: Get notifications notification field.
      operationId: getNotificationsByIdNotificationByField
      x-api-path-slug: notificationsidnotificationfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idNotification
        description: idNotification
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Notifications
      - Notification
      - Field
  /organizations/{idOrg}/membersInvited/{field}:
    get:
      summary: Get Organizations Membersinvited Field
      description: Get organizations membersinvited field.
      operationId: getOrganizationsMembersInvitedByIdOrgByField
      x-api-path-slug: organizationsidorgmembersinvitedfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idOrg
        description: idOrg or name
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Membersinvited
      - Field
  /organizations/{idOrg}/{field}:
    get:
      summary: Get Organizations Field
      description: Get organizations field.
      operationId: getOrganizationsByIdOrgByField
      x-api-path-slug: organizationsidorgfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idOrg
        description: idOrg or name
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Field
  /tokens/{token}/member/{field}:
    get:
      summary: Get Tokens Member Field
      description: Get tokens member field.
      operationId: getTokensMemberByTokenByField
      x-api-path-slug: tokenstokenmemberfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: query
        name: key
        description: Generate your application key
      - in: path
        name: token
        description: token
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Tokens
      - Member
      - Field
  /tokens/{token}/{field}:
    get:
      summary: Get Tokens Field
      description: Get tokens field.
      operationId: getTokensByTokenByField
      x-api-path-slug: tokenstokenfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: query
        name: key
        description: Generate your application key
      - in: path
        name: token
        description: token
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Tokens
      - Field
  /webhooks/{idWebhook}/{field}:
    get:
      summary: Get Webhooks Field
      description: Get webhooks field.
      operationId: getWebhooksByIdWebhookByField
      x-api-path-slug: webhooksidwebhookfield-get
      parameters:
      - in: path
        name: field
        description: field
      - in: path
        name: idWebhook
        description: idWebhook
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Webhooks
      - Field
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---