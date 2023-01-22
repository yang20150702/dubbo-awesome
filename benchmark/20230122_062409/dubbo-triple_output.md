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
# Warmup Iteration   1: 2.050 ops/ms
# Warmup Iteration   2: 5.735 ops/ms
# Warmup Iteration   3: 8.870 ops/ms
Iteration   1: 9.627 ops/ms
Iteration   2: 9.327 ops/ms
Iteration   3: 9.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.414 ±(99.9%) 3.387 ops/ms [Average]
  (min, avg, max) = (9.287, 9.414, 9.627), stdev = 0.186
  CI (99.9%): [6.026, 12.801] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 3.124 ops/ms
# Warmup Iteration   2: 9.055 ops/ms
# Warmup Iteration   3: 9.342 ops/ms
Iteration   1: 9.399 ops/ms
Iteration   2: 9.739 ops/ms
Iteration   3: 9.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.702 ±(99.9%) 5.232 ops/ms [Average]
  (min, avg, max) = (9.399, 9.702, 9.969), stdev = 0.287
  CI (99.9%): [4.470, 14.934] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.057 ops/ms
# Warmup Iteration   2: 8.642 ops/ms
# Warmup Iteration   3: 8.904 ops/ms
Iteration   1: 9.484 ops/ms
Iteration   2: 9.495 ops/ms
Iteration   3: 9.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.546 ±(99.9%) 1.788 ops/ms [Average]
  (min, avg, max) = (9.484, 9.546, 9.659), stdev = 0.098
  CI (99.9%): [7.758, 11.334] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.619 ops/ms
# Warmup Iteration   2: 7.141 ops/ms
# Warmup Iteration   3: 7.686 ops/ms
Iteration   1: 8.179 ops/ms
Iteration   2: 8.008 ops/ms
Iteration   3: 8.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.082 ±(99.9%) 1.599 ops/ms [Average]
  (min, avg, max) = (8.008, 8.082, 8.179), stdev = 0.088
  CI (99.9%): [6.483, 9.682] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.958 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.009 ms/op
Iteration   1: 3.498 ±(99.9%) 0.007 ms/op
Iteration   2: 3.358 ±(99.9%) 0.009 ms/op
Iteration   3: 3.297 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.384 ±(99.9%) 1.880 ms/op [Average]
  (min, avg, max) = (3.297, 3.384, 3.498), stdev = 0.103
  CI (99.9%): [1.505, 5.264] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.165 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.348 ±(99.9%) 0.008 ms/op
Iteration   1: 3.294 ±(99.9%) 0.009 ms/op
Iteration   2: 3.218 ±(99.9%) 0.010 ms/op
Iteration   3: 3.201 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.238 ±(99.9%) 0.900 ms/op [Average]
  (min, avg, max) = (3.201, 3.238, 3.294), stdev = 0.049
  CI (99.9%): [2.338, 4.137] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.365 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.005 ms/op
Iteration   1: 3.500 ±(99.9%) 0.010 ms/op
Iteration   2: 3.450 ±(99.9%) 0.006 ms/op
Iteration   3: 3.304 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.418 ±(99.9%) 1.857 ms/op [Average]
  (min, avg, max) = (3.304, 3.418, 3.500), stdev = 0.102
  CI (99.9%): [1.561, 5.275] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.845 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.006 ms/op
Iteration   1: 3.962 ±(99.9%) 0.010 ms/op
Iteration   2: 3.935 ±(99.9%) 0.008 ms/op
Iteration   3: 3.872 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.923 ±(99.9%) 0.840 ms/op [Average]
  (min, avg, max) = (3.872, 3.923, 3.962), stdev = 0.046
  CI (99.9%): [3.083, 4.763] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.552 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.767 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.010 ms/op
Iteration   1: 3.389 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  18.499 ms/op
                 createUser·p0.9999: 22.464 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   2: 3.458 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.792 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.817 ms/op
                 createUser·p0.999:  21.571 ms/op
                 createUser·p0.9999: 24.306 ms/op
                 createUser·p1.00:   33.063 ms/op

Iteration   3: 3.436 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  16.198 ms/op
                 createUser·p0.9999: 31.775 ms/op
                 createUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279950
  mean =      3.428 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12705 
    [ 2.500,  5.000) = 261256 
    [ 5.000,  7.500) = 4756 
    [ 7.500, 10.000) = 643 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     17.303 ms/op
     p(99.9900) =     31.130 ms/op
     p(99.9990) =     33.037 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.286 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.008 ms/op
Iteration   1: 3.304 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.632 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  11.157 ms/op
                 existUser·p0.9999: 21.234 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   2: 3.276 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.772 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  9.229 ms/op
                 existUser·p0.9999: 24.944 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   3: 3.367 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.337 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  20.513 ms/op
                 existUser·p0.9999: 24.461 ms/op
                 existUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289507
  mean =      3.316 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1811 
    [ 2.500,  5.000) = 283594 
    [ 5.000,  7.500) = 3287 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.337 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     14.769 ms/op
     p(99.9900) =     24.184 ms/op
     p(99.9990) =     25.464 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 8.818 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.011 ms/op
Iteration   1: 3.407 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.767 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   6.989 ms/op
                 getUser·p0.999:  20.025 ms/op
                 getUser·p0.9999: 25.108 ms/op
                 getUser·p1.00:   26.182 ms/op

Iteration   2: 3.441 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  20.939 ms/op
                 getUser·p0.9999: 24.206 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   3: 3.486 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.405 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  13.418 ms/op
                 getUser·p0.9999: 25.297 ms/op
                 getUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278472
  mean =      3.445 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6155 
    [ 2.500,  5.000) = 262625 
    [ 5.000,  7.500) = 8101 
    [ 7.500, 10.000) = 1147 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     24.909 ms/op
     p(99.9990) =     25.934 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 9.576 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.306 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.013 ms/op
Iteration   1: 4.058 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  17.620 ms/op
                 listUser·p0.9999: 25.403 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 3.878 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.500 ms/op
                 listUser·p0.999:  15.434 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   3: 3.990 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241423
  mean =      3.974 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 234113 
    [ 5.000,  7.500) = 5323 
    [ 7.500, 10.000) = 1200 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     16.599 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     25.649 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.414 ± 3.387  ops/ms
ClientPb.existUser                       thrpt       3   9.702 ± 5.232  ops/ms
ClientPb.getUser                         thrpt       3   9.546 ± 1.788  ops/ms
ClientPb.listUser                        thrpt       3   8.082 ± 1.599  ops/ms
ClientPb.createUser                       avgt       3   3.384 ± 1.880   ms/op
ClientPb.existUser                        avgt       3   3.238 ± 0.900   ms/op
ClientPb.getUser                          avgt       3   3.418 ± 1.857   ms/op
ClientPb.listUser                         avgt       3   3.923 ± 0.840   ms/op
ClientPb.createUser                     sample  279950   3.428 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.202           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.186           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.743           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.303           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.130           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.096           ms/op
ClientPb.existUser                      sample  289507   3.316 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.337           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.769           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.184           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.443           ms/op
ClientPb.getUser                        sample  278472   3.445 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.699           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.554           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.926           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.909           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.182           ms/op
ClientPb.listUser                       sample  241423   3.974 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.694           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.160           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.599           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.691           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.821           ms/op
