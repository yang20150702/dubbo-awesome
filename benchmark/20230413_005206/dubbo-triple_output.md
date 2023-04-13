# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.130 ops/ms
# Warmup Iteration   2: 2.284 ops/ms
# Warmup Iteration   3: 5.151 ops/ms
Iteration   1: 5.465 ops/ms
Iteration   2: 5.715 ops/ms
Iteration   3: 6.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.776 ±(99.9%) 6.299 ops/ms [Average]
  (min, avg, max) = (5.465, 5.776, 6.148), stdev = 0.345
  CI (99.9%): [≈ 0, 12.075] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.594 ops/ms
# Warmup Iteration   2: 4.429 ops/ms
# Warmup Iteration   3: 5.804 ops/ms
Iteration   1: 5.714 ops/ms
Iteration   2: 6.107 ops/ms
Iteration   3: 6.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.951 ±(99.9%) 3.799 ops/ms [Average]
  (min, avg, max) = (5.714, 5.951, 6.107), stdev = 0.208
  CI (99.9%): [2.152, 9.750] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.698 ops/ms
# Warmup Iteration   2: 4.946 ops/ms
# Warmup Iteration   3: 5.882 ops/ms
Iteration   1: 6.153 ops/ms
Iteration   2: 6.029 ops/ms
Iteration   3: 6.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.211 ±(99.9%) 3.968 ops/ms [Average]
  (min, avg, max) = (6.029, 6.211, 6.452), stdev = 0.217
  CI (99.9%): [2.244, 10.179] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.548 ops/ms
# Warmup Iteration   2: 4.277 ops/ms
# Warmup Iteration   3: 5.267 ops/ms
Iteration   1: 5.147 ops/ms
Iteration   2: 5.306 ops/ms
Iteration   3: 5.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.345 ±(99.9%) 4.004 ops/ms [Average]
  (min, avg, max) = (5.147, 5.345, 5.581), stdev = 0.219
  CI (99.9%): [1.340, 9.349] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 16.429 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.448 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.418 ±(99.9%) 0.011 ms/op
Iteration   1: 5.311 ±(99.9%) 0.012 ms/op
Iteration   2: 5.279 ±(99.9%) 0.011 ms/op
Iteration   3: 5.517 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.369 ±(99.9%) 2.352 ms/op [Average]
  (min, avg, max) = (5.279, 5.369, 5.517), stdev = 0.129
  CI (99.9%): [3.016, 7.721] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 18.770 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 6.250 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.885 ±(99.9%) 0.011 ms/op
Iteration   1: 5.000 ±(99.9%) 0.010 ms/op
Iteration   2: 4.774 ±(99.9%) 0.012 ms/op
Iteration   3: 4.780 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.851 ±(99.9%) 2.355 ms/op [Average]
  (min, avg, max) = (4.774, 4.851, 5.000), stdev = 0.129
  CI (99.9%): [2.496, 7.206] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 16.620 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.100 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.778 ±(99.9%) 0.020 ms/op
Iteration   1: 5.400 ±(99.9%) 0.009 ms/op
Iteration   2: 5.056 ±(99.9%) 0.008 ms/op
Iteration   3: 5.356 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.270 ±(99.9%) 3.413 ms/op [Average]
  (min, avg, max) = (5.056, 5.270, 5.400), stdev = 0.187
  CI (99.9%): [1.857, 8.684] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 18.831 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 7.489 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.350 ±(99.9%) 0.014 ms/op
Iteration   1: 5.803 ±(99.9%) 0.019 ms/op
Iteration   2: 5.804 ±(99.9%) 0.018 ms/op
Iteration   3: 6.008 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.872 ±(99.9%) 2.157 ms/op [Average]
  (min, avg, max) = (5.803, 5.872, 6.008), stdev = 0.118
  CI (99.9%): [3.715, 8.029] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.151 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 6.876 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.844 ±(99.9%) 0.027 ms/op
Iteration   1: 5.117 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.171 ms/op
                 createUser·p0.50:   4.751 ms/op
                 createUser·p0.90:   6.521 ms/op
                 createUser·p0.95:   7.676 ms/op
                 createUser·p0.99:   10.387 ms/op
                 createUser·p0.999:  22.105 ms/op
                 createUser·p0.9999: 25.518 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   2: 5.120 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.786 ms/op
                 createUser·p0.50:   4.858 ms/op
                 createUser·p0.90:   6.070 ms/op
                 createUser·p0.95:   6.824 ms/op
                 createUser·p0.99:   10.158 ms/op
                 createUser·p0.999:  25.821 ms/op
                 createUser·p0.9999: 34.899 ms/op
                 createUser·p1.00:   34.996 ms/op

Iteration   3: 5.379 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.954 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.709 ms/op
                 createUser·p0.95:   8.036 ms/op
                 createUser·p0.99:   10.928 ms/op
                 createUser·p0.999:  20.316 ms/op
                 createUser·p0.9999: 31.919 ms/op
                 createUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 184497
  mean =      5.202 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 106611 
    [ 5.000,  7.500) = 68230 
    [ 7.500, 10.000) = 7295 
    [10.000, 12.500) = 1480 
    [12.500, 15.000) = 443 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.786 ms/op
     p(50.0000) =      4.858 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     31.952 ms/op
     p(99.9990) =     34.996 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.378 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 6.197 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.104 ±(99.9%) 0.021 ms/op
Iteration   1: 5.049 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.421 ms/op
                 existUser·p0.50:   4.702 ms/op
                 existUser·p0.90:   6.242 ms/op
                 existUser·p0.95:   7.487 ms/op
                 existUser·p0.99:   10.109 ms/op
                 existUser·p0.999:  21.680 ms/op
                 existUser·p0.9999: 27.492 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   2: 5.008 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   5.940 ms/op
                 existUser·p0.95:   6.824 ms/op
                 existUser·p0.99:   9.601 ms/op
                 existUser·p0.999:  25.343 ms/op
                 existUser·p0.9999: 31.550 ms/op
                 existUser·p1.00:   32.440 ms/op

Iteration   3: 5.046 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   4.727 ms/op
                 existUser·p0.90:   6.156 ms/op
                 existUser·p0.95:   7.414 ms/op
                 existUser·p0.99:   10.109 ms/op
                 existUser·p0.999:  29.247 ms/op
                 existUser·p0.9999: 37.398 ms/op
                 existUser·p1.00:   39.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 190682
  mean =      5.034 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 130342 
    [ 5.000,  7.500) = 51910 
    [ 7.500, 10.000) = 6471 
    [10.000, 12.500) = 1188 
    [12.500, 15.000) = 397 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      7.242 ms/op
     p(99.0000) =     10.011 ms/op
     p(99.9000) =     21.827 ms/op
     p(99.9900) =     36.766 ms/op
     p(99.9990) =     38.465 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.313 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 6.304 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.280 ±(99.9%) 0.018 ms/op
Iteration   1: 5.452 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.573 ms/op
                 getUser·p0.50:   5.087 ms/op
                 getUser·p0.90:   6.808 ms/op
                 getUser·p0.95:   8.266 ms/op
                 getUser·p0.99:   10.732 ms/op
                 getUser·p0.999:  23.003 ms/op
                 getUser·p0.9999: 27.698 ms/op
                 getUser·p1.00:   28.180 ms/op

Iteration   2: 5.211 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.503 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.300 ms/op
                 getUser·p0.95:   7.627 ms/op
                 getUser·p0.99:   11.960 ms/op
                 getUser·p0.999:  22.446 ms/op
                 getUser·p0.9999: 28.958 ms/op
                 getUser·p1.00:   32.276 ms/op

Iteration   3: 5.336 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.630 ms/op
                 getUser·p0.50:   5.022 ms/op
                 getUser·p0.90:   6.455 ms/op
                 getUser·p0.95:   7.365 ms/op
                 getUser·p0.99:   10.355 ms/op
                 getUser·p0.999:  23.957 ms/op
                 getUser·p0.9999: 29.951 ms/op
                 getUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 179929
  mean =      5.331 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 93016 
    [ 5.000,  7.500) = 76654 
    [ 7.500, 10.000) = 7584 
    [10.000, 12.500) = 1632 
    [12.500, 15.000) = 621 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.573 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.799 ms/op
     p(99.0000) =     10.977 ms/op
     p(99.9000) =     22.839 ms/op
     p(99.9900) =     28.902 ms/op
     p(99.9990) =     30.915 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.423 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 7.242 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.300 ±(99.9%) 0.029 ms/op
Iteration   1: 6.062 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.142 ms/op
                 listUser·p0.50:   5.579 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   12.026 ms/op
                 listUser·p0.999:  28.320 ms/op
                 listUser·p0.9999: 33.697 ms/op
                 listUser·p1.00:   34.669 ms/op

Iteration   2: 6.106 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   5.685 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  27.689 ms/op
                 listUser·p0.9999: 36.804 ms/op
                 listUser·p1.00:   41.878 ms/op

Iteration   3: 6.117 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.066 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   7.094 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   12.031 ms/op
                 listUser·p0.999:  22.774 ms/op
                 listUser·p0.9999: 25.507 ms/op
                 listUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157354
  mean =      6.095 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10389 
    [ 5.000, 10.000) = 142156 
    [10.000, 15.000) = 4221 
    [15.000, 20.000) = 239 
    [20.000, 25.000) = 146 
    [25.000, 30.000) = 133 
    [30.000, 35.000) = 57 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      5.693 ms/op
     p(90.0000) =      7.348 ms/op
     p(95.0000) =      8.978 ms/op
     p(99.0000) =     11.993 ms/op
     p(99.9000) =     25.952 ms/op
     p(99.9900) =     34.686 ms/op
     p(99.9990) =     41.840 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.776 ± 6.299  ops/ms
ClientPb.existUser                       thrpt       3   5.951 ± 3.799  ops/ms
ClientPb.getUser                         thrpt       3   6.211 ± 3.968  ops/ms
ClientPb.listUser                        thrpt       3   5.345 ± 4.004  ops/ms
ClientPb.createUser                       avgt       3   5.369 ± 2.352   ms/op
ClientPb.existUser                        avgt       3   4.851 ± 2.355   ms/op
ClientPb.getUser                          avgt       3   5.270 ± 3.413   ms/op
ClientPb.listUser                         avgt       3   5.872 ± 2.157   ms/op
ClientPb.createUser                     sample  184497   5.202 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.786           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.858           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.406           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.586           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.568           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.677           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.952           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.996           ms/op
ClientPb.existUser                      sample  190682   5.034 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.772           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.128           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.242           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.011           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.827           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.766           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.059           ms/op
ClientPb.getUser                        sample  179929   5.331 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.573           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.973           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.529           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.799           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.977           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.839           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.902           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.276           ms/op
ClientPb.listUser                       sample  157354   6.095 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.096           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.348           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.978           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.993           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.952           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.686           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.878           ms/op
