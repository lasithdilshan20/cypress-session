# cypress-session

End-to-End Only
Cache and restore cookies, localStorage, and sessionStorage (i.e. session data) in order to recreate a consistent browser context between tests.

The cy.session() command will inherit the testIsolation value to determine whether or not the page is cleared when caching and restoring the browser context.
