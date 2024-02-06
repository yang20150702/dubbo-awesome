# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.936 ops/ms
# Warmup Iteration   2: 12.090 ops/ms
# Warmup Iteration   3: 12.247 ops/ms
Iteration   1: 12.607 ops/ms
Iteration   2: 12.756 ops/ms
Iteration   3: 12.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.722 ±(99.9%) 1.860 ops/ms [Average]
  (min, avg, max) = (12.607, 12.722, 12.801), stdev = 0.102
  CI (99.9%): [10.861, 14.582] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.442 ops/ms
# Warmup Iteration   2: 12.944 ops/ms
# Warmup Iteration   3: 13.041 ops/ms
Iteration   1: 13.083 ops/ms
Iteration   2: 13.075 ops/ms
Iteration   3: 13.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.061 ±(99.9%) 0.580 ops/ms [Average]
  (min, avg, max) = (13.025, 13.061, 13.083), stdev = 0.032
  CI (99.9%): [12.481, 13.641] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.520 ops/ms
# Warmup Iteration   2: 12.449 ops/ms
# Warmup Iteration   3: 12.754 ops/ms
Iteration   1: 12.781 ops/ms
Iteration   2: 12.779 ops/ms
Iteration   3: 12.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.760 ±(99.9%) 0.640 ops/ms [Average]
  (min, avg, max) = (12.720, 12.760, 12.781), stdev = 0.035
  CI (99.9%): [12.120, 13.400] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.861 ops/ms
# Warmup Iteration   2: 10.439 ops/ms
# Warmup Iteration   3: 10.645 ops/ms
Iteration   1: 10.678 ops/ms
Iteration   2: 10.634 ops/ms
Iteration   3: 10.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.672 ±(99.9%) 0.628 ops/ms [Average]
  (min, avg, max) = (10.634, 10.672, 10.702), stdev = 0.034
  CI (99.9%): [10.044, 11.300] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.121 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.004 ms/op
Iteration   1: 2.590 ±(99.9%) 0.003 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.559 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (2.540, 2.559, 2.590), stdev = 0.028
  CI (99.9%): [2.052, 3.065] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.670 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.004 ms/op
Iteration   1: 2.440 ±(99.9%) 0.004 ms/op
Iteration   2: 2.421 ±(99.9%) 0.003 ms/op
Iteration   3: 2.454 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.438 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (2.421, 2.438, 2.454), stdev = 0.017
  CI (99.9%): [2.136, 2.740] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.754 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.003 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.495 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (2.487, 2.495, 2.502), stdev = 0.008
  CI (99.9%): [2.357, 2.632] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.749 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.005 ms/op
Iteration   1: 3.036 ±(99.9%) 0.005 ms/op
Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
Iteration   3: 3.042 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.044 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (3.036, 3.044, 3.056), stdev = 0.010
  CI (99.9%): [2.854, 3.235] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.262 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.660 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.780 ms/op
                 createUser·p0.999:  10.977 ms/op
                 createUser·p0.9999: 14.238 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  9.982 ms/op
                 createUser·p0.9999: 13.160 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  8.251 ms/op
                 createUser·p0.9999: 9.999 ms/op
                 createUser·p1.00:   13.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382067
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 184755 
    [ 2.500,  3.750) = 193100 
    [ 3.750,  5.000) = 3020 
    [ 5.000,  6.250) = 689 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.802 ms/op
     p(99.9000) =      8.257 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     14.375 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.620 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  5.686 ms/op
                 existUser·p0.9999: 13.042 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  7.791 ms/op
                 existUser·p0.9999: 14.861 ms/op
                 existUser·p1.00:   16.286 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.618 ms/op
                 existUser·p0.999:  8.304 ms/op
                 existUser·p0.9999: 11.960 ms/op
                 existUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390230
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 191579 
    [ 2.500,  3.750) = 195076 
    [ 3.750,  5.000) = 2693 
    [ 5.000,  6.250) = 453 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      6.210 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     15.466 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.877 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  7.109 ms/op
                 getUser·p0.9999: 13.397 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.047 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  8.733 ms/op
                 getUser·p0.9999: 12.299 ms/op
                 getUser·p1.00:   13.271 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  8.066 ms/op
                 getUser·p0.9999: 11.646 ms/op
                 getUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382837
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 188723 
    [ 2.500,  3.750) = 189749 
    [ 3.750,  5.000) = 3070 
    [ 5.000,  6.250) = 829 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      7.137 ms/op
     p(99.9900) =     13.009 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.617 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.009 ms/op
Iteration   1: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.821 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  8.880 ms/op
                 listUser·p0.9999: 10.928 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  8.978 ms/op
                 listUser·p0.9999: 10.721 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.761 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 11.155 ms/op
                 listUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317675
  mean =      3.019 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 87461 
    [ 2.500,  3.750) = 191539 
    [ 3.750,  5.000) = 31706 
    [ 5.000,  6.250) = 5670 
    [ 6.250,  7.500) = 564 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 219 
    [10.000, 11.250) = 165 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.148 ms/op
     p(99.9900) =     11.043 ms/op
     p(99.9990) =     11.715 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.722 ± 1.860  ops/ms
ClientPb.existUser                       thrpt       3  13.061 ± 0.580  ops/ms
ClientPb.getUser                         thrpt       3  12.760 ± 0.640  ops/ms
ClientPb.listUser                        thrpt       3  10.672 ± 0.628  ops/ms
ClientPb.createUser                       avgt       3   2.559 ± 0.506   ms/op
ClientPb.existUser                        avgt       3   2.438 ± 0.302   ms/op
ClientPb.getUser                          avgt       3   2.495 ± 0.138   ms/op
ClientPb.listUser                         avgt       3   3.044 ± 0.191   ms/op
ClientPb.createUser                     sample  382067   2.510 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.002           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.802           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.257           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.271           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.466           ms/op
ClientPb.existUser                      sample  390230   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.874           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.210           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.008           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.286           ms/op
ClientPb.getUser                        sample  382837   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.725           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.137           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.009           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.385           ms/op
ClientPb.listUser                       sample  317675   3.019 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.761           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.148           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.043           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.878           ms/op
