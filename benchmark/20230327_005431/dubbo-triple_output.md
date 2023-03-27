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
# Warmup Iteration   1: 1.192 ops/ms
# Warmup Iteration   2: 2.496 ops/ms
# Warmup Iteration   3: 5.473 ops/ms
Iteration   1: 6.080 ops/ms
Iteration   2: 6.310 ops/ms
Iteration   3: 6.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.281 ±(99.9%) 3.434 ops/ms [Average]
  (min, avg, max) = (6.080, 6.281, 6.453), stdev = 0.188
  CI (99.9%): [2.847, 9.715] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.837 ops/ms
# Warmup Iteration   2: 4.978 ops/ms
# Warmup Iteration   3: 6.149 ops/ms
Iteration   1: 6.416 ops/ms
Iteration   2: 6.582 ops/ms
Iteration   3: 6.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.417 ±(99.9%) 2.987 ops/ms [Average]
  (min, avg, max) = (6.254, 6.417, 6.582), stdev = 0.164
  CI (99.9%): [3.430, 9.404] (assumes normal distribution)


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
# Warmup Iteration   1: 1.665 ops/ms
# Warmup Iteration   2: 5.229 ops/ms
# Warmup Iteration   3: 6.051 ops/ms
Iteration   1: 5.927 ops/ms
Iteration   2: 5.908 ops/ms
Iteration   3: 6.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.987 ±(99.9%) 2.213 ops/ms [Average]
  (min, avg, max) = (5.908, 5.987, 6.127), stdev = 0.121
  CI (99.9%): [3.774, 8.200] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.783 ops/ms
# Warmup Iteration   2: 4.805 ops/ms
# Warmup Iteration   3: 5.366 ops/ms
Iteration   1: 5.361 ops/ms
Iteration   2: 5.589 ops/ms
Iteration   3: 5.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.457 ±(99.9%) 2.159 ops/ms [Average]
  (min, avg, max) = (5.361, 5.457, 5.589), stdev = 0.118
  CI (99.9%): [3.298, 7.616] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 17.191 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.422 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.637 ±(99.9%) 0.016 ms/op
Iteration   1: 5.409 ±(99.9%) 0.008 ms/op
Iteration   2: 5.304 ±(99.9%) 0.010 ms/op
Iteration   3: 5.122 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.278 ±(99.9%) 2.651 ms/op [Average]
  (min, avg, max) = (5.122, 5.278, 5.409), stdev = 0.145
  CI (99.9%): [2.627, 7.930] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.306 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.670 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.825 ±(99.9%) 0.012 ms/op
Iteration   1: 4.815 ±(99.9%) 0.009 ms/op
Iteration   2: 5.078 ±(99.9%) 0.006 ms/op
Iteration   3: 4.823 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.906 ±(99.9%) 2.729 ms/op [Average]
  (min, avg, max) = (4.815, 4.906, 5.078), stdev = 0.150
  CI (99.9%): [2.176, 7.635] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 14.728 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 6.919 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.954 ±(99.9%) 0.017 ms/op
Iteration   1: 5.099 ±(99.9%) 0.008 ms/op
Iteration   2: 5.024 ±(99.9%) 0.011 ms/op
Iteration   3: 5.172 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.098 ±(99.9%) 1.345 ms/op [Average]
  (min, avg, max) = (5.024, 5.098, 5.172), stdev = 0.074
  CI (99.9%): [3.754, 6.443] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.890 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.524 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.935 ±(99.9%) 0.009 ms/op
Iteration   1: 5.955 ±(99.9%) 0.009 ms/op
Iteration   2: 5.995 ±(99.9%) 0.012 ms/op
Iteration   3: 5.745 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.898 ±(99.9%) 2.445 ms/op [Average]
  (min, avg, max) = (5.745, 5.898, 5.995), stdev = 0.134
  CI (99.9%): [3.453, 8.344] (assumes normal distribution)


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
# Warmup Iteration   1: 17.220 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 6.377 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.631 ±(99.9%) 0.023 ms/op
Iteration   1: 5.138 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.163 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.242 ms/op
                 createUser·p0.95:   7.365 ms/op
                 createUser·p0.99:   9.880 ms/op
                 createUser·p0.999:  20.986 ms/op
                 createUser·p0.9999: 26.236 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   2: 5.088 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.991 ms/op
                 createUser·p0.50:   4.833 ms/op
                 createUser·p0.90:   6.136 ms/op
                 createUser·p0.95:   6.750 ms/op
                 createUser·p0.99:   9.126 ms/op
                 createUser·p0.999:  22.134 ms/op
                 createUser·p0.9999: 25.854 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   3: 5.195 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.474 ms/op
                 createUser·p0.50:   4.882 ms/op
                 createUser·p0.90:   6.316 ms/op
                 createUser·p0.95:   7.102 ms/op
                 createUser·p0.99:   10.224 ms/op
                 createUser·p0.999:  23.792 ms/op
                 createUser·p0.9999: 32.004 ms/op
                 createUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 186704
  mean =      5.140 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 111589 
    [ 5.000,  7.500) = 67995 
    [ 7.500, 10.000) = 5416 
    [10.000, 12.500) = 1073 
    [12.500, 15.000) = 332 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.991 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.234 ms/op
     p(95.0000) =      7.045 ms/op
     p(99.0000) =      9.683 ms/op
     p(99.9000) =     21.450 ms/op
     p(99.9900) =     30.190 ms/op
     p(99.9990) =     32.150 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 16.388 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 6.054 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.155 ±(99.9%) 0.017 ms/op
Iteration   1: 5.036 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.064 ms/op
                 existUser·p0.50:   4.833 ms/op
                 existUser·p0.90:   5.923 ms/op
                 existUser·p0.95:   6.627 ms/op
                 existUser·p0.99:   9.191 ms/op
                 existUser·p0.999:  25.062 ms/op
                 existUser·p0.9999: 29.642 ms/op
                 existUser·p1.00:   30.507 ms/op

Iteration   2: 5.051 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.167 ms/op
                 existUser·p0.50:   4.809 ms/op
                 existUser·p0.90:   6.021 ms/op
                 existUser·p0.95:   6.849 ms/op
                 existUser·p0.99:   9.388 ms/op
                 existUser·p0.999:  24.547 ms/op
                 existUser·p0.9999: 28.235 ms/op
                 existUser·p1.00:   29.753 ms/op

Iteration   3: 4.969 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.935 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   5.685 ms/op
                 existUser·p0.95:   6.439 ms/op
                 existUser·p0.99:   9.634 ms/op
                 existUser·p0.999:  22.249 ms/op
                 existUser·p0.9999: 28.302 ms/op
                 existUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 191247
  mean =      5.018 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 123573 
    [ 5.000,  7.500) = 61882 
    [ 7.500, 10.000) = 4211 
    [10.000, 12.500) = 899 
    [12.500, 15.000) = 322 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.935 ms/op
     p(50.0000) =      4.809 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      6.676 ms/op
     p(99.0000) =      9.470 ms/op
     p(99.9000) =     24.511 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     30.328 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 18.125 ±(99.9%) 0.263 ms/op
# Warmup Iteration   2: 6.677 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.421 ±(99.9%) 0.019 ms/op
Iteration   1: 5.289 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.241 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.291 ms/op
                 getUser·p0.95:   7.765 ms/op
                 getUser·p0.99:   13.025 ms/op
                 getUser·p0.999:  24.871 ms/op
                 getUser·p0.9999: 27.591 ms/op
                 getUser·p1.00:   28.705 ms/op

Iteration   2: 5.293 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.503 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   6.250 ms/op
                 getUser·p0.95:   8.061 ms/op
                 getUser·p0.99:   10.682 ms/op
                 getUser·p0.999:  20.389 ms/op
                 getUser·p0.9999: 27.230 ms/op
                 getUser·p1.00:   27.886 ms/op

Iteration   3: 5.202 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.101 ms/op
                 getUser·p0.50:   4.940 ms/op
                 getUser·p0.90:   6.169 ms/op
                 getUser·p0.95:   7.274 ms/op
                 getUser·p0.99:   9.519 ms/op
                 getUser·p0.999:  25.193 ms/op
                 getUser·p0.9999: 29.055 ms/op
                 getUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182424
  mean =      5.261 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 99611 
    [ 5.000,  7.500) = 72701 
    [ 7.500, 10.000) = 7202 
    [10.000, 12.500) = 1780 
    [12.500, 15.000) = 633 
    [15.000, 17.500) = 231 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 104 

  Percentiles, ms/op:
      p(0.0000) =      2.101 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.242 ms/op
     p(95.0000) =      7.709 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     22.236 ms/op
     p(99.9900) =     27.820 ms/op
     p(99.9990) =     29.776 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 19.149 ±(99.9%) 0.310 ms/op
# Warmup Iteration   2: 7.002 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.296 ±(99.9%) 0.022 ms/op
Iteration   1: 5.986 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.736 ms/op
                 listUser·p0.50:   5.571 ms/op
                 listUser·p0.90:   7.283 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   11.895 ms/op
                 listUser·p0.999:  23.298 ms/op
                 listUser·p0.9999: 27.284 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   2: 5.982 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.724 ms/op
                 listUser·p0.50:   5.661 ms/op
                 listUser·p0.90:   7.062 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  25.084 ms/op
                 listUser·p0.9999: 33.663 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   3: 5.842 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   6.562 ms/op
                 listUser·p0.95:   7.274 ms/op
                 listUser·p0.99:   10.125 ms/op
                 listUser·p0.999:  18.359 ms/op
                 listUser·p0.9999: 22.662 ms/op
                 listUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 161648
  mean =      5.936 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 13251 
    [ 5.000,  7.500) = 137606 
    [ 7.500, 10.000) = 8173 
    [10.000, 12.500) = 1750 
    [12.500, 15.000) = 438 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.441 ms/op
     p(50.0000) =      5.636 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      8.004 ms/op
     p(99.0000) =     10.977 ms/op
     p(99.9000) =     22.818 ms/op
     p(99.9900) =     32.293 ms/op
     p(99.9990) =     34.169 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.281 ± 3.434  ops/ms
ClientPb.existUser                       thrpt       3   6.417 ± 2.987  ops/ms
ClientPb.getUser                         thrpt       3   5.987 ± 2.213  ops/ms
ClientPb.listUser                        thrpt       3   5.457 ± 2.159  ops/ms
ClientPb.createUser                       avgt       3   5.278 ± 2.651   ms/op
ClientPb.existUser                        avgt       3   4.906 ± 2.729   ms/op
ClientPb.getUser                          avgt       3   5.098 ± 1.345   ms/op
ClientPb.listUser                         avgt       3   5.898 ± 2.445   ms/op
ClientPb.createUser                     sample  186704   5.140 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.991           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.841           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.234           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.045           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.683           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.450           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.190           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.178           ms/op
ClientPb.existUser                      sample  191247   5.018 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.935           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.882           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.676           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.470           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.511           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.869           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.507           ms/op
ClientPb.getUser                        sample  182424   5.261 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.101           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.709           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.485           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.236           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.820           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.884           ms/op
ClientPb.listUser                       sample  161648   5.936 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.441           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.971           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.004           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.977           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.818           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.293           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.210           ms/op
