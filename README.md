"packageDirectories"
 /* CSS library import fix in test context. See:
  https://github.com/salesforce/sfdx-lwc-jest/issues/288) */
  '^c/cssLibrary$':
      '/force-app/main/default/lwc/cssLibrary/cssLibrary.css',
  // Jest mocks
  '^@salesforce/apex$': '/force-app/test/jest-mocks/apex',
  '^@salesforce/schema$': '/force-app/test/jest-mocks/schema',
  '^lightning/navigation$':
      '/force-app/test/jest-mocks/lightning/navigation',
      
