# Change log

## 0.2.31 (2020-09-08)

Updated minimum version requirements for gems

### Changed

## 0.2.30 (2020-06-18)

### Changed

- Added task for adding codecov.yml to project.
  Please run for create/update  codecov.yml:
  ```
    rake shuttlerock_shared_config:update_codecov  # Update codecov.yml
  ```

- Added new cops to rubocop.yml:
    Layout/EmptyLinesAroundAttributeAccessor (0.83)
    Lint/DeprecatedOpenSSLConstant (0.84)
    Lint/MixedRegexpCaptureTypes (0.85)
    Style/RedundantRegexpCharacterClass (0.85)
    Style/RedundantRegexpEscape (0.85)
    Style/SlicingWithRange (0.83)

## 0.2.29 (2020-05-05)

### Changed

- Added new cops to rubocop.yml:
    Lint/RaiseException (0.81)
    Lint/StructNewOverride (0.81)
    Style/HashEachMethods (0.80)
    Style/HashTransformKeys (0.80)
    Style/HashTransformValues (0.80)


## 0.2.28 (2020-04-29)

### Changed

- Updated ruby to 2.6.6


## 0.2.27 (2020-03-06)

### Changed
- Added task for adding PULL_REQUEST_TEMPLATE.md to project.
  Please run for create/update  .github/PULL_REQUEST_TEMPLATE.md:
  ```
    rake shuttlerock_shared_config:update_pull_request_template  # Update PULL_REQUEST_TEMPLATE.md
  ```
- Updated command shuttlerock_shared_config:update. Now command include update_pull_request_template

## 0.2.26 (2019-01-16)

### Changed
- Include a department for each problem cop in .rubocop.yml.
  Please run for update .rubocop.yml:
  ```
    rake shuttlerock_shared_config:update_rubocop      # Update .rubocop.yml
  ```

## 0.2.23 (2019-10-05)

### Changed
- Include a department for each problem cop in .rubocop.yml.
  Please run for update .rubocop.yml:
  ```
    rake shuttlerock_shared_config:update_rubocop      # Update .rubocop.yml
  ```

## 0.2.22 (2019-10-05)

### Changed

- Update dependencies
