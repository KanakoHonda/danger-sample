Dir.chdir("DangerSample") do
	android_lint.gradle_task = "app:lint"
	android_lint.report_file = "app/build/reports/lint-results.xml"
	android_lint.filtering = false 
	android_lint.lint(inline_mode: true)
end
