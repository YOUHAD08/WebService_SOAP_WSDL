# Bank Web Service Project

This project demonstrates a SOAP-based web service for banking operations, developed using JAX-WS. The service offers functionalities such as currency conversion and account management. Testing is conducted using SoapUI, and a client application is implemented to interact with the service.

## Table of Contents

1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Web Service Implementation](#web-service-implementation)
   - [Currency Conversion Operation](#currency-conversion-operation)
   - [Account Retrieval Operations](#account-retrieval-operations)
4. [Testing with SoapUI](#testing-with-soapui)
5. [Client Application](#client-application)


## Introduction

The Bank Web Service project illustrates the development of a SOAP web service using JAX-WS. It provides operations for currency conversion and account management, tested with SoapUI, and includes a client application for service consumption.

## Project Structure

<img src="WebServiceImage/Project Structure.png" alt="">

## Web Service Implementation

The `BankService` class defines the web service with the following operations:

<img src="WebServiceImage/WebService.png" alt="">

### Currency Conversion Operation

The `Currency_Change` method converts an amount in Euros to Moroccan Dirhams (DH) using a fixed exchange rate.

### Account Retrieval Operations

- **`Get_Account`**: Fetches account details corresponding to a specified Bank ID.
- **`Get_Accounts`**: Retrieves a comprehensive list of all accounts.

## Testing with SoapUI

### Test `The Currency_Change` method

<img src="WebServiceImage/SOAPUI Test_1.png" alt="">

### Test `Get_Account` method

<img src="WebServiceImage/SOAPUI Test_2.png" alt="">

### Test `Get_Accounts` method

<img src="WebServiceImage/SOAPUI Test_3.png" alt="">

## Client Application

<img src="WebServiceImage/Client_1 Test.png" alt="">
