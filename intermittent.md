<h4>Spec</h4>

`Member Billing Page Single bundle with 1 product when subscription-bundle with 1 plans should
have bundle product details`

`spec/features/spaces/bundles/bundle_details_spec.rb:48`

<h4>Error</h4>

`Failure/Error: self.status = STATUSES[:empty]
NoMethodError:
       undefined method status=' for #<Asset:0x00007fa0e72abc48>`

------------------------------------------------------------------------------------------------

<h4>Spec</h4>

`spec/features/onboarding_visit_paid_network_one_plan_spec.rb:28`

<h4>Error</h4>

`expected not to find visible css "#join-widget .join-button" within
#<Capybara::Node::Element tag="div" path="/HTML/BODY[1]/DIV[5]/DIV[1]/DIV[1]/DIV[1]/DIV[1]">,
found 1 match: "Join Us"`

`Failure/Error: expect(page).to have_no_css(locator, visible: true)
  expected not to find visible css "#join-widget .join-button" within
  #<Capybara::Node::Element tag="div" path="/HTML/BODY[1]/DIV[5]/DIV[1]/DIV[1]/DIV[1]/DIV[1]">,
  found 1 match: "Join Us"`

<h4>Jenkins build</h4>
https://build.mightystate.com/job/speckel_master/1627/testReport/junit/spec.features/onboarding_visit_paid_network_one_plan_spec/ci_node_4___Artifacts___Onboarding_Visit_Visiting_an_existing_Paid_Network_with_a_single_payment_plan_it_should_behave_like_Paid_Onboarding_in_a_Public_Circle_as_a_non_member_of_the_Circle__but_a_member_of_the_Community_when_joining_and_signing_in/

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<h4>Spec</h4>

`spec/features/spaces/member_billing_spec`

`Member Billing Page Validate Your Purchases page Validated purchased bundle page when paid subscription bundle should validate purchased bundle page for subscription`

<h4>Error</h4>

`RSpec::Expectations::MultipleExpectationsNotMetError`

`spec/spec_helper.rb:298:in block (2 levels) in <top (required)>`
`home/cloudbees-jenkins-distribution/.rvm/gems/ruby-2.4.6/gems/knapsack_pro-1.14.0/lib/knapsack_pro/adapters/rspec_adapter.rb:35:in block (2 levels) in bind_time_tracker'`

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<h4>Spec</h4>

 `spec/features/courses/locking_spec`

 `Locking as a host can lock the lessons`

<h4>Error</h4>

`expected not to find visible css "#flyout-overlay" within #<Capybara::Node::Element tag="body" path="/HTML/BODY[1]">, found 1 match: ""`

-------------------------------------------------------------------------------------------------------------------------------------------------------

<h4>Spec</h4>

`spec/features/taxes/taxes_spec:34`

`taxes linked quaderno account and tax collection enabled host can unlink quaderno account`

<h4>Error</h4>

`expected true got false`

<h5>`Failure/Error: expect(page.evaluate_script "$('#proceed-with-checkbox-input').prop('checked')").to be true`</h5>

---------------------------------------------------------------------------------------------------------------------------------------------------------------
<h4>Spec</h4>

`spec/features/spaces/settings/checklist_spec:78`

`Checklist Settings as host should be able to complete achievements`


<h4>Error</h4>

`Failure/Error: expect(page).to have_css(locator, options)
  expected to find visible css "#edit-landing-description-layout-modal" but there were no matches. Also found "", which matched the selector but not all filters.`

<h4>Jenkins Build</h4>
https://build.mightystate.com/job/speckel_branch_pipeline/job/iain%252Fmn-18464-create-circle/lastCompletedBuild/testReport/spec.features.spaces.settings/checklist_spec/ci_node_7___Artifacts___Checklist_Settings_as_host_should_be_able_to_complete_the_achievements/

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<h4>Spec</h4>

`spec/features/courses/editing_visibility_spec.rb:834`

<h4>Error</h4>

`Failure/Error: expect(page).to have_content('Hidden')
  expected to find text "Hidden" in "Visible". (However, it was found 1 time including non-visible text.)`

<h4>Jenkins Build</h4>
https://build.mightystate.com/blue/organizations/jenkins/speckel_branch_pipeline/detail/andrea_taxes_3/8/tests

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
