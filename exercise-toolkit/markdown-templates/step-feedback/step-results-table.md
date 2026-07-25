## Step ${{ vars.step_number }} Results

| Check | Status |
|-------|--------|
| Checked for updated minimist version in package.json | ${{ vars.package_json_check_passed == 'true' && '✅ Passed' || '❌ Failed' }} |
| Checked for updated minimist version in package-lock.json | ${{ vars.package_lock_check_passed == 'true' && '✅ Passed' || '❌ Failed' }} |
