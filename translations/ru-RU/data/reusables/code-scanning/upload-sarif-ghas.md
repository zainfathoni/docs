{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.22" or currentVersion == "github-ae@latest" %}

{% note %}

**Note:** Uploading SARIF data to display as {% data variables.product.prodname_code_scanning %} results in {% data variables.product.product_name %} is supported for organization-owned repositories with {% data variables.product.prodname_GH_advanced_security %} enabled{% if currentVersion == "free-pro-team@latest" %}, and public repositories on {% data variables.product.prodname_dotcom_the_website %}{% endif %}. For more information, see "[Managing security and analysis settings for your repository](/github/administering-a-repository/managing-security-and-analysis-settings-for-your-repository)."

{% endnote %}

{% endif %}
