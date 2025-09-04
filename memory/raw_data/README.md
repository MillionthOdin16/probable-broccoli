# Memory - Raw Data

This directory stores unprocessed information that the Synapse Agent encounters but hasn't yet analyzed or integrated into its knowledge base.

## Types of Raw Data

### External Information
- API responses
- Web scraping results  
- Documentation from external sources
- Research papers or articles
- User-provided datasets

### System Information
- Error logs and stack traces
- Performance metrics
- Configuration files
- Build outputs
- Test results

### Temporary Downloads
- Files downloaded for analysis
- Backups before major changes
- Experimental data
- Reference materials

## File Organization
```
/raw_data/
├── external/           # Information from outside sources
├── system/            # Internal system data
├── downloads/         # Temporary downloaded files
└── archive/           # Older raw data that may still be useful
```

## Processing Workflow
1. **Ingestion**: Raw data saved here immediately upon receipt
2. **Analysis**: Data examined and key insights extracted
3. **Integration**: Relevant insights moved to `/knowledge/` directory
4. **Archival**: Original raw data moved to archive or deleted if no longer needed

## Data Lifecycle
- **Fresh**: Recently received, needs processing
- **Processing**: Currently being analyzed
- **Processed**: Analysis complete, insights extracted
- **Archived**: Kept for potential future reference
- **Deleted**: No longer useful, safely removed

## Access Patterns
The agent should regularly scan this directory for:
- New data requiring processing
- Old data that can be archived or deleted
- Patterns across multiple raw data sources
- Quality issues that need attention

---
*This directory is currently empty but will populate as the agent encounters and stores raw information.*