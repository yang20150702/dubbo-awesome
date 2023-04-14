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
# Warmup Iteration   1: 2.487 ops/ms
# Warmup Iteration   2: 6.845 ops/ms
# Warmup Iteration   3: 9.287 ops/ms
Iteration   1: 9.593 ops/ms
Iteration   2: 10.038 ops/ms
Iteration   3: 10.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.907 ±(99.9%) 4.986 ops/ms [Average]
  (min, avg, max) = (9.593, 9.907, 10.090), stdev = 0.273
  CI (99.9%): [4.920, 14.893] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.367 ops/ms
# Warmup Iteration   2: 9.365 ops/ms
# Warmup Iteration   3: 10.137 ops/ms
Iteration   1: 10.129 ops/ms
Iteration   2: 10.182 ops/ms
Iteration   3: 10.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.171 ±(99.9%) 0.679 ops/ms [Average]
  (min, avg, max) = (10.129, 10.171, 10.201), stdev = 0.037
  CI (99.9%): [9.491, 10.850] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.101 ops/ms
# Warmup Iteration   2: 9.074 ops/ms
# Warmup Iteration   3: 9.542 ops/ms
Iteration   1: 9.994 ops/ms
Iteration   2: 9.795 ops/ms
Iteration   3: 10.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.931 ±(99.9%) 2.140 ops/ms [Average]
  (min, avg, max) = (9.795, 9.931, 10.003), stdev = 0.117
  CI (99.9%): [7.791, 12.071] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.463 ops/ms
# Warmup Iteration   2: 7.727 ops/ms
# Warmup Iteration   3: 8.125 ops/ms
Iteration   1: 8.532 ops/ms
Iteration   2: 8.568 ops/ms
Iteration   3: 8.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.505 ±(99.9%) 1.449 ops/ms [Average]
  (min, avg, max) = (8.416, 8.505, 8.568), stdev = 0.079
  CI (99.9%): [7.057, 9.954] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.845 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.006 ms/op
Iteration   1: 3.244 ±(99.9%) 0.005 ms/op
Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
Iteration   3: 3.102 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.161 ±(99.9%) 1.346 ms/op [Average]
  (min, avg, max) = (3.102, 3.161, 3.244), stdev = 0.074
  CI (99.9%): [1.815, 4.507] (assumes normal distribution)


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
# Warmup Iteration   1: 7.347 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.372 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.004 ms/op
Iteration   1: 3.080 ±(99.9%) 0.005 ms/op
Iteration   2: 3.057 ±(99.9%) 0.009 ms/op
Iteration   3: 3.110 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.083 ±(99.9%) 0.486 ms/op [Average]
  (min, avg, max) = (3.057, 3.083, 3.110), stdev = 0.027
  CI (99.9%): [2.596, 3.569] (assumes normal distribution)


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
# Warmup Iteration   1: 8.242 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.007 ms/op
Iteration   1: 3.262 ±(99.9%) 0.003 ms/op
Iteration   2: 3.092 ±(99.9%) 0.004 ms/op
Iteration   3: 3.095 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.150 ±(99.9%) 1.775 ms/op [Average]
  (min, avg, max) = (3.092, 3.150, 3.262), stdev = 0.097
  CI (99.9%): [1.374, 4.925] (assumes normal distribution)


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
# Warmup Iteration   1: 9.389 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.992 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.009 ms/op
Iteration   1: 3.689 ±(99.9%) 0.005 ms/op
Iteration   2: 3.704 ±(99.9%) 0.006 ms/op
Iteration   3: 3.778 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.724 ±(99.9%) 0.867 ms/op [Average]
  (min, avg, max) = (3.689, 3.724, 3.778), stdev = 0.048
  CI (99.9%): [2.857, 4.591] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.514 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.009 ms/op
Iteration   1: 3.138 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 24.852 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  19.071 ms/op
                 createUser·p0.9999: 24.503 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   3: 3.148 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.450 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  17.629 ms/op
                 createUser·p0.9999: 21.434 ms/op
                 createUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305590
  mean =      3.137 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14228 
    [ 2.500,  5.000) = 286851 
    [ 5.000,  7.500) = 3526 
    [ 7.500, 10.000) = 499 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 181 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     24.492 ms/op
     p(99.9990) =     25.297 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.507 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
Iteration   1: 3.085 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  12.222 ms/op
                 existUser·p0.9999: 22.598 ms/op
                 existUser·p1.00:   23.036 ms/op

Iteration   2: 3.087 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.423 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.776 ms/op
                 existUser·p0.999:  8.798 ms/op
                 existUser·p0.9999: 21.451 ms/op
                 existUser·p1.00:   21.955 ms/op

Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  12.078 ms/op
                 existUser·p0.9999: 20.438 ms/op
                 existUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310096
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13243 
    [ 2.500,  5.000) = 292456 
    [ 5.000,  7.500) = 3707 
    [ 7.500, 10.000) = 346 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     11.646 ms/op
     p(99.9900) =     21.528 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.413 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.010 ms/op
Iteration   1: 3.375 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  15.853 ms/op
                 getUser·p0.9999: 19.546 ms/op
                 getUser·p1.00:   20.054 ms/op

Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  12.531 ms/op
                 getUser·p0.9999: 20.111 ms/op
                 getUser·p1.00:   21.496 ms/op

Iteration   3: 3.175 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  13.626 ms/op
                 getUser·p0.9999: 28.670 ms/op
                 getUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298196
  mean =      3.218 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22180 
    [ 2.500,  5.000) = 269989 
    [ 5.000,  7.500) = 5253 
    [ 7.500, 10.000) = 342 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 157 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     27.701 ms/op
     p(99.9990) =     29.756 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.643 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.223 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.011 ms/op
Iteration   1: 3.703 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.753 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.141 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  15.110 ms/op
                 listUser·p0.9999: 21.082 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   2: 3.738 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  12.845 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   3: 3.718 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.137 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  13.238 ms/op
                 listUser·p0.9999: 15.876 ms/op
                 listUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257837
  mean =      3.720 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 252351 
    [ 5.000,  7.500) = 3744 
    [ 7.500, 10.000) = 1049 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.798 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     21.322 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.907 ± 4.986  ops/ms
ClientPb.existUser                       thrpt       3  10.171 ± 0.679  ops/ms
ClientPb.getUser                         thrpt       3   9.931 ± 2.140  ops/ms
ClientPb.listUser                        thrpt       3   8.505 ± 1.449  ops/ms
ClientPb.createUser                       avgt       3   3.161 ± 1.346   ms/op
ClientPb.existUser                        avgt       3   3.083 ± 0.486   ms/op
ClientPb.getUser                          avgt       3   3.150 ± 1.775   ms/op
ClientPb.listUser                         avgt       3   3.724 ± 0.867   ms/op
ClientPb.createUser                     sample  305590   3.137 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.077           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.432           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.055           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.492           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.526           ms/op
ClientPb.existUser                      sample  310096   3.094 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.178           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.359           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.646           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.528           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.036           ms/op
ClientPb.getUser                        sample  298196   3.218 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.161           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.554           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.665           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.701           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.917           ms/op
ClientPb.listUser                       sample  257837   3.720 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.696           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.178           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.783           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.798           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.956           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.823           ms/op
