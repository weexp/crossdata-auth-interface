@Library('libpipelines@feature/multibranch') _

hose {
    EMAIL = 'crossdata'
    MODULE = 'crossdata-auth'
    DEVTIMEOUT = 20
    RELEASETIMEOUT = 20
    REPOSITORY = 'crossdata-auth-interface'
    
    DEV = { config ->        
        doPackage(config)
        doDeploy(config)            
    }
}
