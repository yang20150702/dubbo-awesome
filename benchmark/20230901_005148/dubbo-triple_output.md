# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.073 ops/ms
# Warmup Iteration   2: 2.308 ops/ms
# Warmup Iteration   3: 5.384 ops/ms
Iteration   1: 5.616 ops/ms
Iteration   2: 5.838 ops/ms
Iteration   3: 5.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.807 ±(99.9%) 3.249 ops/ms [Average]
  (min, avg, max) = (5.616, 5.807, 5.968), stdev = 0.178
  CI (99.9%): [2.558, 9.056] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.654 ops/ms
# Warmup Iteration   2: 4.856 ops/ms
# Warmup Iteration   3: 5.677 ops/ms
Iteration   1: 6.042 ops/ms
Iteration   2: 6.147 ops/ms
Iteration   3: 6.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.096 ±(99.9%) 0.959 ops/ms [Average]
  (min, avg, max) = (6.042, 6.096, 6.147), stdev = 0.053
  CI (99.9%): [5.137, 7.054] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.716 ops/ms
# Warmup Iteration   2: 4.758 ops/ms
# Warmup Iteration   3: 5.729 ops/ms
Iteration   1: 5.801 ops/ms
Iteration   2: 5.771 ops/ms
Iteration   3: 5.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.805 ±(99.9%) 0.677 ops/ms [Average]
  (min, avg, max) = (5.771, 5.805, 5.844), stdev = 0.037
  CI (99.9%): [5.129, 6.482] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.572 ops/ms
# Warmup Iteration   2: 4.175 ops/ms
# Warmup Iteration   3: 5.050 ops/ms
Iteration   1: 4.982 ops/ms
Iteration   2: 5.156 ops/ms
Iteration   3: 5.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.094 ±(99.9%) 1.761 ops/ms [Average]
  (min, avg, max) = (4.982, 5.094, 5.156), stdev = 0.097
  CI (99.9%): [3.333, 6.855] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.214 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.680 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.966 ±(99.9%) 0.011 ms/op
Iteration   1: 5.629 ±(99.9%) 0.011 ms/op
Iteration   2: 5.663 ±(99.9%) 0.010 ms/op
Iteration   3: 5.684 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.659 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (5.629, 5.659, 5.684), stdev = 0.028
  CI (99.9%): [5.145, 6.173] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.120 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.723 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.269 ±(99.9%) 0.010 ms/op
Iteration   1: 5.315 ±(99.9%) 0.007 ms/op
Iteration   2: 5.158 ±(99.9%) 0.011 ms/op
Iteration   3: 5.192 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.221 ±(99.9%) 1.509 ms/op [Average]
  (min, avg, max) = (5.158, 5.221, 5.315), stdev = 0.083
  CI (99.9%): [3.713, 6.730] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 15.919 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 6.291 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.472 ±(99.9%) 0.011 ms/op
Iteration   1: 5.352 ±(99.9%) 0.014 ms/op
Iteration   2: 5.569 ±(99.9%) 0.010 ms/op
Iteration   3: 5.672 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.531 ±(99.9%) 2.977 ms/op [Average]
  (min, avg, max) = (5.352, 5.531, 5.672), stdev = 0.163
  CI (99.9%): [2.554, 8.508] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 20.309 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 8.720 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 7.030 ±(99.9%) 0.008 ms/op
Iteration   1: 6.639 ±(99.9%) 0.010 ms/op
Iteration   2: 6.499 ±(99.9%) 0.015 ms/op
Iteration   3: 6.469 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.535 ±(99.9%) 1.657 ms/op [Average]
  (min, avg, max) = (6.469, 6.535, 6.639), stdev = 0.091
  CI (99.9%): [4.878, 8.192] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.881 ±(99.9%) 0.275 ms/op
# Warmup Iteration   2: 8.029 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 5.939 ±(99.9%) 0.027 ms/op
Iteration   1: 5.575 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.073 ms/op
                 createUser·p0.50:   5.317 ms/op
                 createUser·p0.90:   7.045 ms/op
                 createUser·p0.95:   8.077 ms/op
                 createUser·p0.99:   10.633 ms/op
                 createUser·p0.999:  20.633 ms/op
                 createUser·p0.9999: 27.936 ms/op
                 createUser·p1.00:   28.312 ms/op

Iteration   2: 5.513 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.415 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   6.980 ms/op
                 createUser·p0.95:   7.990 ms/op
                 createUser·p0.99:   10.846 ms/op
                 createUser·p0.999:  20.809 ms/op
                 createUser·p0.9999: 25.526 ms/op
                 createUser·p1.00:   25.854 ms/op

Iteration   3: 5.462 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.931 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.816 ms/op
                 createUser·p0.95:   7.840 ms/op
                 createUser·p0.99:   11.120 ms/op
                 createUser·p0.999:  25.017 ms/op
                 createUser·p0.9999: 29.877 ms/op
                 createUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173843
  mean =      5.516 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 68684 
    [ 5.000,  7.500) = 93490 
    [ 7.500, 10.000) = 8987 
    [10.000, 12.500) = 1820 
    [12.500, 15.000) = 465 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.939 ms/op
     p(95.0000) =      7.971 ms/op
     p(99.0000) =     10.813 ms/op
     p(99.9000) =     22.544 ms/op
     p(99.9900) =     29.053 ms/op
     p(99.9990) =     31.495 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 17.157 ±(99.9%) 0.265 ms/op
# Warmup Iteration   2: 6.642 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.943 ±(99.9%) 0.026 ms/op
Iteration   1: 6.033 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   1.217 ms/op
                 existUser·p0.50:   5.497 ms/op
                 existUser·p0.90:   8.356 ms/op
                 existUser·p0.95:   9.626 ms/op
                 existUser·p0.99:   12.763 ms/op
                 existUser·p0.999:  26.508 ms/op
                 existUser·p0.9999: 32.244 ms/op
                 existUser·p1.00:   33.063 ms/op

Iteration   2: 5.961 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   5.415 ms/op
                 existUser·p0.90:   8.323 ms/op
                 existUser·p0.95:   9.634 ms/op
                 existUser·p0.99:   12.485 ms/op
                 existUser·p0.999:  19.346 ms/op
                 existUser·p0.9999: 33.423 ms/op
                 existUser·p1.00:   33.620 ms/op

Iteration   3: 5.678 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   2.327 ms/op
                 existUser·p0.50:   5.218 ms/op
                 existUser·p0.90:   7.750 ms/op
                 existUser·p0.95:   9.273 ms/op
                 existUser·p0.99:   12.405 ms/op
                 existUser·p0.999:  29.734 ms/op
                 existUser·p0.9999: 37.945 ms/op
                 existUser·p1.00:   38.732 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 163009
  mean =      5.887 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 50283 
    [ 5.000,  7.500) = 91013 
    [ 7.500, 10.000) = 15447 
    [10.000, 12.500) = 4568 
    [12.500, 15.000) = 1084 
    [15.000, 17.500) = 258 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      8.184 ms/op
     p(95.0000) =      9.503 ms/op
     p(99.0000) =     12.532 ms/op
     p(99.9000) =     21.103 ms/op
     p(99.9900) =     36.988 ms/op
     p(99.9990) =     38.484 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 19.263 ±(99.9%) 0.308 ms/op
# Warmup Iteration   2: 7.230 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.641 ±(99.9%) 0.024 ms/op
Iteration   1: 5.383 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.310 ms/op
                 getUser·p0.50:   5.030 ms/op
                 getUser·p0.90:   6.791 ms/op
                 getUser·p0.95:   8.151 ms/op
                 getUser·p0.99:   10.600 ms/op
                 getUser·p0.999:  24.452 ms/op
                 getUser·p0.9999: 36.643 ms/op
                 getUser·p1.00:   38.273 ms/op

Iteration   2: 5.635 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.757 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   7.610 ms/op
                 getUser·p0.95:   8.536 ms/op
                 getUser·p0.99:   11.092 ms/op
                 getUser·p0.999:  19.634 ms/op
                 getUser·p0.9999: 29.426 ms/op
                 getUser·p1.00:   30.081 ms/op

Iteration   3: 5.622 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   7.168 ms/op
                 getUser·p0.95:   8.176 ms/op
                 getUser·p0.99:   11.476 ms/op
                 getUser·p0.999:  27.699 ms/op
                 getUser·p0.9999: 42.992 ms/op
                 getUser·p1.00:   43.778 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173054
  mean =      5.544 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 74553 
    [ 5.000, 10.000) = 95425 
    [10.000, 15.000) = 2566 
    [15.000, 20.000) = 283 
    [20.000, 25.000) = 80 
    [25.000, 30.000) = 72 
    [30.000, 35.000) = 29 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      5.128 ms/op
     p(90.0000) =      7.266 ms/op
     p(95.0000) =      8.298 ms/op
     p(99.0000) =     11.043 ms/op
     p(99.9000) =     23.162 ms/op
     p(99.9900) =     41.726 ms/op
     p(99.9990) =     43.730 ms/op
     p(99.9999) =     43.778 ms/op
    p(100.0000) =     43.778 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.240 ±(99.9%) 0.327 ms/op
# Warmup Iteration   2: 7.594 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.681 ±(99.9%) 0.029 ms/op
Iteration   1: 6.562 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.695 ms/op
                 listUser·p0.50:   6.111 ms/op
                 listUser·p0.90:   8.438 ms/op
                 listUser·p0.95:   9.847 ms/op
                 listUser·p0.99:   13.337 ms/op
                 listUser·p0.999:  24.815 ms/op
                 listUser·p0.9999: 30.675 ms/op
                 listUser·p1.00:   31.982 ms/op

Iteration   2: 6.736 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   6.259 ms/op
                 listUser·p0.90:   8.602 ms/op
                 listUser·p0.95:   10.109 ms/op
                 listUser·p0.99:   13.959 ms/op
                 listUser·p0.999:  28.295 ms/op
                 listUser·p0.9999: 36.143 ms/op
                 listUser·p1.00:   37.159 ms/op

Iteration   3: 6.581 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   6.078 ms/op
                 listUser·p0.90:   8.421 ms/op
                 listUser·p0.95:   10.322 ms/op
                 listUser·p0.99:   13.705 ms/op
                 listUser·p0.999:  24.599 ms/op
                 listUser·p0.9999: 28.255 ms/op
                 listUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144875
  mean =      6.625 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 6609 
    [ 5.000,  7.500) = 113376 
    [ 7.500, 10.000) = 17352 
    [10.000, 12.500) = 5154 
    [12.500, 15.000) = 1662 
    [15.000, 17.500) = 379 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      6.152 ms/op
     p(90.0000) =      8.487 ms/op
     p(95.0000) =     10.076 ms/op
     p(99.0000) =     13.648 ms/op
     p(99.9000) =     25.792 ms/op
     p(99.9900) =     33.622 ms/op
     p(99.9990) =     37.012 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.807 ± 3.249  ops/ms
ClientPb.existUser                       thrpt       3   6.096 ± 0.959  ops/ms
ClientPb.getUser                         thrpt       3   5.805 ± 0.677  ops/ms
ClientPb.listUser                        thrpt       3   5.094 ± 1.761  ops/ms
ClientPb.createUser                       avgt       3   5.659 ± 0.514   ms/op
ClientPb.existUser                        avgt       3   5.221 ± 1.509   ms/op
ClientPb.getUser                          avgt       3   5.531 ± 2.977   ms/op
ClientPb.listUser                         avgt       3   6.535 ± 1.657   ms/op
ClientPb.createUser                     sample  173843   5.516 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.415           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.939           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.971           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.813           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.544           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.053           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.785           ms/op
ClientPb.existUser                      sample  163009   5.887 ± 0.016   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.928           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.374           ms/op
ClientPb.existUser:existUser·p0.90      sample           8.184           ms/op
ClientPb.existUser:existUser·p0.95      sample           9.503           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.532           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.103           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.988           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.732           ms/op
ClientPb.getUser                        sample  173054   5.544 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.809           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.128           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.266           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.298           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.043           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.162           ms/op
ClientPb.getUser:getUser·p0.9999        sample          41.726           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.778           ms/op
ClientPb.listUser                       sample  144875   6.625 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.448           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.152           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.487           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.076           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.648           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.792           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.622           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.159           ms/op
