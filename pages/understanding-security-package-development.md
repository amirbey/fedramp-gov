---
layout: page
title: Understanding Security Package Development
permalink: /understanding-security-package-development/
tag: starting-security-package-development
---
<p>A FedRAMP security package is a comprehensive documentation of a Cloud Service Offering’s (CSO) system security. A FedRAMP security package provides a: </p>
<ul>
<li>Complete system description,</li>
<li>Complete detail of the system’s security control implementation,</li>
<li>Overview of the system’s assessment and assessment methodology, and</li>
<li>Risk assessment that identifies the offering's risk posture, to be used by a Federal customer to make a risk-based authorization decision.</li>
</ul>
<p>Security packages can be exhaustive documents and require effective project management and resourcing from CSPs to see through completion from start to finish. Below is a list of documents included in a standard FedRAMP security package:</p>
<ul>
<li>System Security Plan (SSP) (and attachments)</li>
<li>Security Assessment Plan (SAP)</li>
<li>Security Assessment Report (SAR)</li>
<li>Plan of Actions & Milestones (POA&M)</li>
<li>Continuous Monitoring Plan</li>
<li>Signed Provisional Authority to Operate (P-ATO) for JAB or signed Authority to Operate (ATO) for Agency Authorizations</li>
</ul>
<p>The documents, templates, and blogs below should be read before beginning security documentation and should help stakeholders grasp a better understanding of what the PMO will be looking for in the documentation phase.</p>
<table>
<tr>
<th>Documents</th>
<th>Templates</th>
<th>Blogs</th>
</tr>
<td>
<ul>
<li><a href="{{site.baseurl}}/assets/resources/documents/FedRAMP_Security_Assessment_Framework.pdf">Security Assessment Framework</a></li>
<li><a href="{{site.baseurl}}/assets/resources/documents/FedRAMP_Security_Controls_Baseline.xlsx">FedRAMP Security Controls Baseline</a></li>
<li><a href="{{site.baseurl}}/assets/resources/documents/FedRAMP_General_Document_Acceptance_Criteria.pdf">FedRAMP General Document Acceptance Criteria</a></li>
<li><a href="{{site.baseurl}}/assets/resources/documents/CSP_Agency_Authorization_Best_Practices_for_CSPs.pdf">Agency Authorization Best Practices for CSPs</a></li>
<li><a href="{{site.baseurl}}/assets/resources/documents/CSP_A_FedRAMP_Authorization_Boundary_Guidance.pdf">FedRAMP Authorization Boundary Guidance</a></li>
<li><a href="{{site.baseurl}}/assets/resources/documents/CSP_Digital_Identity_Requirements.pdf">Digital Identity Requirements</a></li>	
<li><a href="{{site.baseurl}}/assets/resources/documents/CSP_Penetration_Test_Guidance.pdf">Penetration Test Guidance</a></li>
<li><a href="{{site.baseurl}}/assets/resources/documents/CSP_TLS_Requirements.pdf">Transport Layer Security (TLS) Requirements</a></li>
<li><a href="{{site.baseurl}}/assets/resources/documents/CSP_Timeliness_and_Accuracy_of_Testing_Requirements.pdf">Timeliness and Accuracy of Testing Requirements</a></li>
</ul>
</td>
<td>
<ul>
<li><a href="{{site.baseurl}}/assets/resources/templates/FedRAMP-Initial-Authorization-Package-Checklist.xls">FedRAMP Initial Authorization Package Checklist</a></li>
</ul>
</td>
<td>
<ul>
{% for post in site.tags[page.tag] %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date: "%B %-d %Y" }})<br>
    {{ post.description }}
  </li>
{% endfor %}
</ul>
</td>
