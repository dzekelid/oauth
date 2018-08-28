swagger: "2.0"
x-collection-name: Meetup
x-complete: 1
info:
  title: Meetup
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /:urlname:
    post:
      summary: Group Edit
      description: Allows organizers to edit their Meetup group information. To change
        group topics, see the [add](/meetup_api/docs/:urlname/topics/#add) and [remove](/meetup_api/docs/:urlname/topics/#remove)
        topics endpoints. To change group photo use the [Group photo upload](/meetup_api/docs/2/group_photo/#create)
        endpoint. OAuth authenticated requests require an additional [group_edit](/meetup_api/auth/#oauth2-scopes)
        permission.
      operationId: groups
      x-api-path-slug: urlname-post
      parameters:
      - in: query
        name: add_topics
        description: Comma-delimited list of topic ids to associate with group
        type: string
      - in: query
        name: country
        description: The ISO_3166-1 country code for the country which contains the
          city
        type: string
      - in: query
        name: description
        description: Summary of what the Meetup group is about in simple HTML format
        type: string
      - in: query
        name: dryrun
        description: Boolean parameter that will cause this endpoint to apply all
          validation rules without actually saving changes in which case the response
          will only reflect the groups current attributes
        type: string
      - in: query
        name: ga_code
        description: Google Analytics code for group
        type: string
      - in: query
        name: join_mode
        description: Controls how members are let into the group
        type: string
      - in: query
        name: key_photo
        description: Groups primary photo
        type: string
      - in: query
        name: list_addr
        description: Mailing list prefix
        type: string
      - in: query
        name: list_mode
        description: Defines policy for who can post to the group mailing list
        type: string
      - in: query
        name: name
        description: Display name of the group
        type: string
      - in: query
        name: photo_req
        description: Indicates that a member must provide a photo before joining
        type: string
      - in: query
        name: questions_req
        description: Indicates that provided questions are required before joining
        type: string
      - in: query
        name: question_edit_{id}
        description: Edits a current profile question identified by an id in the parameter
          name
        type: string
      - in: query
        name: question_{index}
        description: A new profile question defined in the order of index provided
          in the request parameter name
        type: string
      - in: query
        name: remove_topics
        description: Comma-delimited list of topic ids to disassociate with group
        type: string
      - in: query
        name: urlname
        description: Name used for the groups web address on meetup
        type: string
      - in: query
        name: visibility
        description: Restricts group visibility for non-members
        type: string
      - in: query
        name: welcome_message
        description: Message sent to members after they join
        type: string
      - in: query
        name: who
        description: What members of the group will be called
        type: string
      - in: query
        name: zip
        description: The ZIP code of the city
        type: string
      - in: query
        name: '{service}_uri'
        description: A URI for a social network service
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Groups
  /:urlname/topics:
    post:
      summary: Group Topics Add
      description: Associates topics with a given Meetup group. Limited to organizers
        of the group. OAuth authenticated requests require an additional [group_edit](/meetup_api/auth/#oauth2-scopes)
        permission.
      operationId: groups
      x-api-path-slug: urlnametopics-post
      parameters:
      - in: query
        name: topic_id
        description: Comma-delimited list of topic ids to associate with group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Photos
    delete:
      summary: Group Topics Remove
      description: Disassociates topics with a given Meetup group. Limited to organizers
        of the group. OAuth authenticated requests require an additional [group_edit](/meetup_api/auth/#oauth2-scopes)
        permission.
      operationId: groups
      x-api-path-slug: urlnametopics-delete
      parameters:
      - in: query
        name: topic_id
        description: Comma-delimited list of topic ids to disassociate with group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Photos