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
# Warmup Iteration   1: 4.810 ops/ms
# Warmup Iteration   2: 11.618 ops/ms
# Warmup Iteration   3: 12.166 ops/ms
Iteration   1: 12.373 ops/ms
Iteration   2: 12.552 ops/ms
Iteration   3: 12.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.457 ±(99.9%) 1.643 ops/ms [Average]
  (min, avg, max) = (12.373, 12.457, 12.552), stdev = 0.090
  CI (99.9%): [10.814, 14.100] (assumes normal distribution)


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
# Warmup Iteration   1: 8.031 ops/ms
# Warmup Iteration   2: 12.765 ops/ms
# Warmup Iteration   3: 12.880 ops/ms
Iteration   1: 13.069 ops/ms
Iteration   2: 12.909 ops/ms
Iteration   3: 12.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.955 ±(99.9%) 1.819 ops/ms [Average]
  (min, avg, max) = (12.886, 12.955, 13.069), stdev = 0.100
  CI (99.9%): [11.136, 14.774] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.896 ops/ms
# Warmup Iteration   2: 12.252 ops/ms
# Warmup Iteration   3: 12.415 ops/ms
Iteration   1: 12.611 ops/ms
Iteration   2: 12.660 ops/ms
Iteration   3: 12.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.600 ±(99.9%) 1.226 ops/ms [Average]
  (min, avg, max) = (12.528, 12.600, 12.660), stdev = 0.067
  CI (99.9%): [11.374, 13.826] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.652 ops/ms
# Warmup Iteration   2: 10.256 ops/ms
# Warmup Iteration   3: 10.403 ops/ms
Iteration   1: 10.446 ops/ms
Iteration   2: 10.564 ops/ms
Iteration   3: 10.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.518 ±(99.9%) 1.145 ops/ms [Average]
  (min, avg, max) = (10.446, 10.518, 10.564), stdev = 0.063
  CI (99.9%): [9.373, 11.663] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.068 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.003 ms/op
Iteration   1: 2.574 ±(99.9%) 0.004 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.498 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.530 ±(99.9%) 0.724 ms/op [Average]
  (min, avg, max) = (2.498, 2.530, 2.574), stdev = 0.040
  CI (99.9%): [1.805, 3.254] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.766 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
Iteration   1: 2.514 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.508 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.503, 2.508, 2.514), stdev = 0.006
  CI (99.9%): [2.407, 2.608] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.191 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.004 ms/op
Iteration   1: 2.537 ±(99.9%) 0.004 ms/op
Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
Iteration   3: 2.541 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.540 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (2.537, 2.540, 2.542), stdev = 0.003
  CI (99.9%): [2.492, 2.587] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.878 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.005 ms/op
Iteration   2: 3.031 ±(99.9%) 0.005 ms/op
Iteration   3: 3.014 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.022 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (3.014, 3.022, 3.031), stdev = 0.009
  CI (99.9%): [2.861, 3.184] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.309 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  11.512 ms/op
                 createUser·p0.9999: 13.685 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  9.369 ms/op
                 createUser·p0.9999: 12.452 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.953 ms/op
                 createUser·p0.999:  8.124 ms/op
                 createUser·p0.9999: 10.693 ms/op
                 createUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381321
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 183514 
    [ 2.500,  3.750) = 194108 
    [ 3.750,  5.000) = 2850 
    [ 5.000,  6.250) = 356 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      8.135 ms/op
     p(99.9900) =     13.247 ms/op
     p(99.9990) =     13.897 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  11.909 ms/op
                 existUser·p0.9999: 14.029 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 13.846 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.994 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.068 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  5.675 ms/op
                 existUser·p0.9999: 11.814 ms/op
                 existUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382207
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 187668 
    [ 2.500,  3.750) = 191589 
    [ 3.750,  5.000) = 2108 
    [ 5.000,  6.250) = 429 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      6.347 ms/op
     p(99.9900) =     13.646 ms/op
     p(99.9990) =     14.249 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  12.009 ms/op
                 getUser·p0.9999: 14.582 ms/op
                 getUser·p1.00:   15.122 ms/op

Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  9.885 ms/op
                 getUser·p0.9999: 13.353 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  8.483 ms/op
                 getUser·p0.9999: 11.846 ms/op
                 getUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381560
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 188321 
    [ 2.500,  3.750) = 188116 
    [ 3.750,  5.000) = 3802 
    [ 5.000,  6.250) = 772 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.741 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 4.878 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.009 ms/op
Iteration   1: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.697 ms/op
                 listUser·p0.9999: 11.337 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   2: 3.048 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.669 ms/op
                 listUser·p0.50:   2.988 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.725 ms/op
                 listUser·p0.999:  9.637 ms/op
                 listUser·p0.9999: 11.027 ms/op
                 listUser·p1.00:   12.698 ms/op

Iteration   3: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 12.020 ms/op
                 listUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315983
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 89131 
    [ 2.500,  3.750) = 186443 
    [ 3.750,  5.000) = 32571 
    [ 5.000,  6.250) = 6155 
    [ 6.250,  7.500) = 821 
    [ 7.500,  8.750) = 250 
    [ 8.750, 10.000) = 239 
    [10.000, 11.250) = 188 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.683 ms/op
     p(99.9900) =     11.698 ms/op
     p(99.9990) =     12.461 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.457 ± 1.643  ops/ms
ClientPb.existUser                       thrpt       3  12.955 ± 1.819  ops/ms
ClientPb.getUser                         thrpt       3  12.600 ± 1.226  ops/ms
ClientPb.listUser                        thrpt       3  10.518 ± 1.145  ops/ms
ClientPb.createUser                       avgt       3   2.530 ± 0.724   ms/op
ClientPb.existUser                        avgt       3   2.508 ± 0.100   ms/op
ClientPb.getUser                          avgt       3   2.540 ± 0.048   ms/op
ClientPb.listUser                         avgt       3   3.022 ± 0.161   ms/op
ClientPb.createUser                     sample  381321   2.515 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.783           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.135           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.247           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.943           ms/op
ClientPb.existUser                      sample  382207   2.511 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.959           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.347           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.646           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.582           ms/op
ClientPb.getUser                        sample  381560   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.649           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.749           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.779           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.122           ms/op
ClientPb.listUser                       sample  315983   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.669           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.683           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.698           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.698           ms/op
