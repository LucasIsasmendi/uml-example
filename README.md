# Sovereign Software Architecture

An uml approach to explain liquid democracy software.

### Table of Diagrams

- [1. User Story](#1-user-story)
- [2. Use Case](#2-use-case)
- [3. Component](#3-component)
- [4. Activity](#4-activity)
  * [4.1 Proposals](#41-proposals)
  * [4.2 Vote Power](#42-vote-power)

## 1. User Story

### 1.1 Basic
| ID# | User Story                                                                          | 
|------|-------------------------------------------------------------------------------------| 
| 1    | As a guest or user, I want to explore proposals/statements                          | 
| 2    | As a guest or user, I want to see the proposals/statements made by an specific user | 
| 3    | As a guest or user, I want to search proposals/statements by hashtags(#)            | 
| 4    | As a guest or user, I want to search proposals/statements by scope(~)               | 

### 1.2 Account and Profile
| ID# | User Story                                                                                                                              | 
|------|-----------------------------------------------------------------------------------------------------------------------------------------| 
| 5    | As a guest, I want to signup into the app using an email, name and password                                                             | 
| 6    | As a user, I want to change my nationality (tribe), my digital id (digital name), my real name (first name and surname) and add a photo | 
| 7    | As a user, I want to be able to log out of the app.                                                                                     | 

### 1.3 Proposals
| ID# | User Story                                                                                         | 
|------|----------------------------------------------------------------------------------------------------| 
| 8    | As a user, I want to create a proposal/statement and see it in the main feed                       | 
| 9    | As a user, I want to update/edit/delete my proposals/statements before they recibe a reply or vote | 
| 10   | As a user, I want to reply to other users proposals/statements                                     | 

### 1.4 Votes
| ID# | User Story                                                             | 
|------|------------------------------------------------------------------------| 
| 11   | As a user, I want to vote on proposals/statements                      | 
| 12   | As a user, I want to unvote proposals                                  | 
| 13   | As a user, I want to delegate vote power to other user                 | 
| 14   | As a user, I want to revoke vote power from other user                 | 
| 15   | As a user, I want to see the list of people I delegate votes to        | 
| 16   | As a user, I want to see the list of people that delegates votes to me | 

### 1.5 Scopes
| ID# | User Story                                                  | 
|------|-------------------------------------------------------------| 
| 17   | As a user, I can create a scope type                        | 
| 18   | As a user, I can create a scope and link it to a scope type | 
| 19   | As a user, I want to be able to join and leave a scope      | 

## 2. Use Case

<p align="center">
<img src="uml/use-case.png" width="400" title="Use Case Diagram">
</p>

## 3. Component

<p align="center">
<img src="uml/component.png" width="400" title="Component Diagram">
</p>

## 4. Activity

### 4.1 Proposals

#### Create Proposal

<p align="center">
<img src="uml/activity/proposals/create.png" width="400" title="Activity Create Proposal Diagram">
</p>

#### Vote Proposal

<p align="center">
<img src="uml/activity/proposals/vote.png" width="400" title="Activity Vote Proposal Diagram">
</p>

#### Unvote Proposal

<p align="center">
<img src="uml/activity/proposals/unvote.png" width="400" title="Activity Unvote Proposal Diagram">
</p>


### 4.2 Vote Power

#### Delegate

<p align="center">
<img src="uml/activity/vote-power/delegate.png" width="400" title="Activity Delegate Vote Power Diagram">
</p>

#### Revoke

<p align="center">
<img src="uml/activity/vote-power/revoke.png" width="400" title="Activity Delegate Vote Power Diagram">
</p>

