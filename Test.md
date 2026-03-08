


## 
```text
/home/alex/anaconda3/envs/LiveCodeBench/bin/python3.11 /home/alex/workspaces/LiveBench/livebench/gen_api_answer.py --model qwen2.5-coder:3b --api-base http://127.0.0.1:11434/v1 --bench-name live_bench/coding/coding_completion --question-source jsonl --livebench-release-option 2024-11-25 --max-tokens 32000 


```

conda activate LiveBench

python run_livebench.py --model qwen2.5-coder:3b --api-base http://127.0.0.1:11434/v1 --max-tokens 32000  --bench-name live_bench/coding/coding_completion --question-source jsonl --livebench-release-option 2024-11-25 --debug

python run_livebench.py --model qwen2.5:7b --api-base http://127.0.0.1:11434/v1 --max-tokens 32000  --bench-name live_bench/coding/coding_completion --question-source jsonl --livebench-release-option 2024-11-25 --debug


python run_livebench.py --model qwen3.5:9b --api-base http://127.0.0.1:11434/v1 --max-tokens 32000  --bench-name live_bench/coding/coding_completion --question-source jsonl --livebench-release-option 2024-11-25 --debug



python show_livebench_result.py --bench-name live_bench/coding/coding_completion --livebench-release-option 2024-11-25





python run_livebench.py --model qwen2.5-coder:3b --api-base http://host.docker.internal:11434/v1 --max-tokens 32000  --bench-name live_bench/coding/coding_completion --question-source jsonl --livebench-release-option 2024-11-25 --debug

python run_livebench.py --model qwen2.5:7b --api-base http://host.docker.internal:11434/v1 --max-tokens 32000  --bench-name live_bench/coding/coding_completion --question-source jsonl --livebench-release-option 2024-11-25 --debug

python show_livebench_result.py --bench-name live_bench/coding/coding_completion --question-source jsonl --livebench-release-option 2024-11-25


python show_livebench_result.py --bench-name live_bench --question-source jsonl --livebench-release-option 2024-11-25

python show_livebench_result.py --bench-name live_bench/coding/coding_completion --question-source jsonl --livebench-release-option 2024-11-25

python show_livebench_result.py  --question-source jsonl --livebench-release-option 2024-11-25




python run_livebench.py --model qwen2.5-coder:3b --api-base http://host.docker.internal:11434/v1 --max-tokens 32000  --bench-name live_bench --question-source jsonl --livebench-release-option 2024-11-25 --debug

python run_livebench.py --model qwen2.5:7b --api-base http://host.docker.internal:11434/v1 --max-tokens 32000  --bench-name live_bench --question-source jsonl --livebench-release-option 2024-11-25 --debug

python show_livebench_result.py --bench-name live_bench --question-source jsonl --livebench-release-option 2024-11-25










