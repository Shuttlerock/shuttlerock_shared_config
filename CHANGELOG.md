# Change log

### Changed

## 0.3.0 (2022-05-23)

- Updated required ruby version to ~> 3.0.0
- Updated rubocop version to allow current ~> 1.0 version
- Updated rake version to allow current ~> 13.0 version
- Add dependabot config
- Add github actions workflow
- Fix github PR template
- Update CircleCI image names
- Update rubocop config:
  - Add new cops
  - Add rubocop-rspec
  - Enable new cops
  - Target ruby v3

## 0.2.32 (2020-10-01)

### Changed

- Added task for updating .gitleaks.toml/gitleaks.yml.
  Please run for create/update .gitleaks.toml/gitleaks.yml:
  ```
    rake shuttlerock_shared_config:update_gitleaks  # Update .gitleaks.toml/gitleaks.yml
  ```

- Added new cops to rubocop.yml:
    Layout/BeginEndAlignment: # (new in 0.91)
    Enabled: true
    Lint/ConstantDefinitionInBlock: # (new in 0.91)
    Enabled: true
    Lint/DuplicateRequire: # (new in 0.90)
    Enabled: true
    Lint/EmptyFile: # (new in 0.90)
    Enabled: true
    Lint/IdentityComparison: # (new in 0.91)
    Enabled: true
    Lint/TrailingCommaInAttributeDeclaration: # (new in 0.90)
    Enabled: true
    Lint/UselessMethodDefinition: # (new in 0.90)
    Enabled: true
    Lint/UselessTimes: # (new in 0.91)
    Enabled: true
    Style/CombinableLoops: # (new in 0.90)
    Enabled: true
    Style/KeywordParametersOrder: # (new in 0.90)
    Enabled: true
    Style/RedundantSelfAssignment: # (new in 0.90)
    Enabled: true
    Style/SoleNestedConditional: # (new in 0.89)
    Enabled: true
    Performance/Sum: # (new in 1.8)
    Enabled: true
    Rails/AfterCommitOverride: # (new in 2.8)
    Enabled: true
    Rails/SquishedSQLHeredocs: # (new in 2.8)
    Enabled: true
    Rails/WhereNot: # (new in 2.8)
    Enabled: true

## 0.2.31 (2020-09-08)

- Updated minimum version requirements for gems

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
