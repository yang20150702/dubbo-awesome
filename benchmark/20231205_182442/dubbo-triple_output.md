# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.672 ops/ms
# Warmup Iteration   2: 11.956 ops/ms
# Warmup Iteration   3: 12.201 ops/ms
Iteration   1: 12.516 ops/ms
Iteration   2: 12.577 ops/ms
Iteration   3: 12.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.686 ±(99.9%) 4.450 ops/ms [Average]
  (min, avg, max) = (12.516, 12.686, 12.966), stdev = 0.244
  CI (99.9%): [8.237, 17.136] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.195 ops/ms
# Warmup Iteration   2: 13.006 ops/ms
# Warmup Iteration   3: 13.052 ops/ms
Iteration   1: 12.841 ops/ms
Iteration   2: 13.112 ops/ms
Iteration   3: 13.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.995 ±(99.9%) 2.538 ops/ms [Average]
  (min, avg, max) = (12.841, 12.995, 13.112), stdev = 0.139
  CI (99.9%): [10.457, 15.533] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.708 ops/ms
# Warmup Iteration   2: 12.605 ops/ms
# Warmup Iteration   3: 13.028 ops/ms
Iteration   1: 13.054 ops/ms
Iteration   2: 13.031 ops/ms
Iteration   3: 12.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.012 ±(99.9%) 0.987 ops/ms [Average]
  (min, avg, max) = (12.951, 13.012, 13.054), stdev = 0.054
  CI (99.9%): [12.025, 13.999] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.831 ops/ms
# Warmup Iteration   2: 10.436 ops/ms
# Warmup Iteration   3: 10.516 ops/ms
Iteration   1: 10.688 ops/ms
Iteration   2: 10.587 ops/ms
Iteration   3: 10.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.636 ±(99.9%) 0.926 ops/ms [Average]
  (min, avg, max) = (10.587, 10.636, 10.688), stdev = 0.051
  CI (99.9%): [9.710, 11.562] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.856 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.492 ±(99.9%) 0.003 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.495 ±(99.9%) 0.075 ms/op [Average]
  (min, avg, max) = (2.492, 2.495, 2.499), stdev = 0.004
  CI (99.9%): [2.419, 2.570] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.619 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
Iteration   1: 2.426 ±(99.9%) 0.004 ms/op
Iteration   2: 2.452 ±(99.9%) 0.003 ms/op
Iteration   3: 2.415 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.431 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (2.415, 2.431, 2.452), stdev = 0.019
  CI (99.9%): [2.087, 2.774] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.108 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.003 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
Iteration   3: 2.508 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.494 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (2.477, 2.494, 2.508), stdev = 0.016
  CI (99.9%): [2.207, 2.781] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.952 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.005 ms/op
Iteration   1: 3.045 ±(99.9%) 0.004 ms/op
Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
Iteration   3: 3.047 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.049 ±(99.9%) 0.104 ms/op [Average]
  (min, avg, max) = (3.045, 3.049, 3.056), stdev = 0.006
  CI (99.9%): [2.945, 3.154] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.140 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
Iteration   1: 2.519 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.837 ms/op
                 createUser·p0.999:  11.601 ms/op
                 createUser·p0.9999: 14.172 ms/op
                 createUser·p1.00:   15.024 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  9.532 ms/op
                 createUser·p0.9999: 11.451 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.963 ms/op
                 createUser·p0.999:  8.219 ms/op
                 createUser·p0.9999: 11.026 ms/op
                 createUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380958
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 181133 
    [ 2.500,  3.750) = 195463 
    [ 3.750,  5.000) = 3331 
    [ 5.000,  6.250) = 543 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.819 ms/op
     p(99.9000) =      8.225 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     14.932 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.663 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  6.191 ms/op
                 existUser·p0.9999: 23.724 ms/op
                 existUser·p1.00:   24.707 ms/op

Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  7.875 ms/op
                 existUser·p0.9999: 12.745 ms/op
                 existUser·p1.00:   13.468 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  6.873 ms/op
                 existUser·p0.9999: 12.368 ms/op
                 existUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393668
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 201661 
    [ 2.500,  5.000) = 190948 
    [ 5.000,  7.500) = 666 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      7.347 ms/op
     p(99.9900) =     21.582 ms/op
     p(99.9990) =     24.349 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.032 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.961 ms/op
                 getUser·p0.999:  11.724 ms/op
                 getUser·p0.9999: 13.744 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  9.635 ms/op
                 getUser·p0.9999: 14.500 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  9.531 ms/op
                 getUser·p0.9999: 12.637 ms/op
                 getUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381902
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 189050 
    [ 2.500,  3.750) = 186400 
    [ 3.750,  5.000) = 5218 
    [ 5.000,  6.250) = 692 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      4.084 ms/op
     p(99.9000) =      9.540 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     14.896 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.611 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.008 ms/op
Iteration   1: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.734 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.831 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.782 ms/op
                 listUser·p0.9999: 10.967 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   2: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  8.880 ms/op
                 listUser·p0.9999: 11.348 ms/op
                 listUser·p1.00:   12.501 ms/op

Iteration   3: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 10.833 ms/op
                 listUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324048
  mean =      2.960 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 102941 
    [ 2.500,  3.750) = 184172 
    [ 3.750,  5.000) = 29741 
    [ 5.000,  6.250) = 5772 
    [ 6.250,  7.500) = 704 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 243 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     10.945 ms/op
     p(99.9990) =     12.224 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.686 ± 4.450  ops/ms
ClientPb.existUser                       thrpt       3  12.995 ± 2.538  ops/ms
ClientPb.getUser                         thrpt       3  13.012 ± 0.987  ops/ms
ClientPb.listUser                        thrpt       3  10.636 ± 0.926  ops/ms
ClientPb.createUser                       avgt       3   2.495 ± 0.075   ms/op
ClientPb.existUser                        avgt       3   2.431 ± 0.343   ms/op
ClientPb.getUser                          avgt       3   2.494 ± 0.287   ms/op
ClientPb.listUser                         avgt       3   3.049 ± 0.104   ms/op
ClientPb.createUser                     sample  380958   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.700           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.819           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.225           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.238           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.024           ms/op
ClientPb.existUser                      sample  393668   2.436 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.891           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.458           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.347           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.582           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.707           ms/op
ClientPb.getUser                        sample  381902   2.512 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.810           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.084           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.540           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.730           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.254           ms/op
ClientPb.listUser                       sample  324048   2.960 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.734           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.946           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.945           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.501           ms/op
