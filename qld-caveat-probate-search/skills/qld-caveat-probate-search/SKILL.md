---
name: qld-caveat-probate-search
description: >-
  Run the Queensland Supreme Court Caveat/Probate Search on the public Online
  Services Portal before a probate matter proceeds. Use when the Queensland
  Probate Checklist says "Do Caveat/Probate Search", or when staff ask whether
  a deceased already has a caveat, probate, letters of administration, or
  other wills-and-estates filing in Queensland.
---

# Queensland Caveat / Probate Search

The court site was checked on 12 October 2026. This skill carries out the office step “Do Caveat/Probate Search”, the first item under Initial Steps on the Queensland Probate Checklist.

## The one search page

Open this URL. Do not substitute another court search.

https://onlineservicesportal.courts.qld.gov.au/probate/search

The page title is **Search for Supreme Court of Queensland Wills and Estates applications**. Court help for the same search:

https://www.courts.qld.gov.au/services-and-online-actions/file-searches/Searching-for-wills-probates-and-administration-documents

Two neighbouring URLs exist. The court assigns them other jobs. Do not use them for this checklist step.

1. Party search (eCourts), https://apps.courts.qld.gov.au/esearching/Search.aspx — the probate search page says this is for court files **not** related to wills and estates.
2. Login, https://onlineservicesportal.courts.qld.gov.au/login — a separate page with **Login with Digital ID** and **QLD Government login using SSO**. Practitioner instructions use that login to **lodge** a wills-and-estates application. The search form itself has no login, no account chooser, and no solicitor mode. A search for surname Brown returned 1,366 rows, and a search for a name that is not on the index returned “No results found”, both without visiting `/login`.

## How to search

Leave **Application type** empty. The dropdown contains Caveat, Citation, Election, Letters of Administration on Intestacy, Letters of Administration with the Will, Order to Administer, Probate, Renunciation, Request for Exemplification, the four Reseal types, and Revocation. Choosing one type hides the others. A caveat-only filter would miss a probate already filed for the same person.

Leave **Filing location** empty. The options are Brisbane, Cairns, Rockhampton, and Townsville. One surname search returned files in all four registries. A Brisbane-only filter would miss the others.

Leave **File number**, filing dates, and event dates empty unless you already have a file number such as `SE00000/24`.

Type the deceased’s given name and last name. The form has no date-of-death field. The court requires exact spelling unless you use `*` as a wildcard.

If the deceased has another surname or given name on the death certificate or the will, run the same search again for that name. Still leave type and location empty.

Click **Search**.

## How to read the result

Each row shows court file reference number, application type, deceased name, filing location, and filed date. Open a row that might be the same person. The card adds the applicant, the legal representative, and a document list (form name and date). The card says full document copies are a separate **search and copy** application. Do not start that paid application as part of this step.

**Clear.** The page says “No results found” / “Sorry, we were not able to find any results matching your search criteria” for every name you searched (legal name and any alias), after one wildcard retry where the spelling was uncertain. Record that sentence, the names you typed, and the date. The checklist step is done. Continue the run-sheet.

The court’s own empty-state text says to refine and search again. A first empty result after a narrow spelling is not yet clear. Retry with `*` on the uncertain part of the name, then record the second result.

**Not this person.** A row whose deceased name is a different given name, or a different surname, is a different estate. Surname-only search of Brown returned 1,366 rows of other people. Ignore those rows. Do not call the search a hit because the surname matched.

**Hit. Stop and hand the row to the lawyer.** A row whose deceased name is this person (given name and surname, allowing for case and middle names) is a hit, whatever the application type is. Record the file number, application type, filing location, filed date, applicant, and legal representative. Stop the probate run-sheet at this step and tell the lawyer. Do not decide whether the firm can still apply. The page does not label rows as granted, pending, or expired. It labels them by application type and filing date.

The court states two limits in plain text. The search cannot confirm that a will is the most current version. The search cannot guarantee the validity of a will where probate or letters of administration have been applied for but not yet granted. Repeat those two limits in the note when you report a hit.

## What to write down

Write a short note the matter file can keep. Include the date, the URL, each name searched, and either “no matching deceased” or the matching rows (file number, type, location, filed date, applicant, representative). The free search does not produce a PDF. A screenshot of the result list is optional. Do not invent a SILQ task or a OneDrive folder for this step.
