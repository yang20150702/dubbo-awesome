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
# Warmup Iteration   1: 4.748 ops/ms
# Warmup Iteration   2: 12.267 ops/ms
# Warmup Iteration   3: 12.480 ops/ms
Iteration   1: 12.783 ops/ms
Iteration   2: 12.701 ops/ms
Iteration   3: 12.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.716 ±(99.9%) 1.116 ops/ms [Average]
  (min, avg, max) = (12.664, 12.716, 12.783), stdev = 0.061
  CI (99.9%): [11.600, 13.832] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.702 ops/ms
# Warmup Iteration   2: 12.814 ops/ms
# Warmup Iteration   3: 12.802 ops/ms
Iteration   1: 12.904 ops/ms
Iteration   2: 12.916 ops/ms
Iteration   3: 12.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.906 ±(99.9%) 0.181 ops/ms [Average]
  (min, avg, max) = (12.897, 12.906, 12.916), stdev = 0.010
  CI (99.9%): [12.725, 13.087] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.373 ops/ms
# Warmup Iteration   2: 12.335 ops/ms
# Warmup Iteration   3: 12.614 ops/ms
Iteration   1: 12.587 ops/ms
Iteration   2: 12.602 ops/ms
Iteration   3: 12.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.575 ±(99.9%) 0.639 ops/ms [Average]
  (min, avg, max) = (12.535, 12.575, 12.602), stdev = 0.035
  CI (99.9%): [11.936, 13.213] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.647 ops/ms
# Warmup Iteration   2: 10.400 ops/ms
# Warmup Iteration   3: 10.398 ops/ms
Iteration   1: 10.385 ops/ms
Iteration   2: 10.539 ops/ms
Iteration   3: 10.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.439 ±(99.9%) 1.583 ops/ms [Average]
  (min, avg, max) = (10.385, 10.439, 10.539), stdev = 0.087
  CI (99.9%): [8.856, 12.022] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.051 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.004 ms/op
Iteration   1: 2.586 ±(99.9%) 0.004 ms/op
Iteration   2: 2.636 ±(99.9%) 0.004 ms/op
Iteration   3: 2.589 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.604 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (2.586, 2.604, 2.636), stdev = 0.028
  CI (99.9%): [2.090, 3.117] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.928 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.488 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.493 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.496 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.488, 2.496, 2.506), stdev = 0.009
  CI (99.9%): [2.332, 2.660] (assumes normal distribution)


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.003 ms/op
Iteration   1: 2.512 ±(99.9%) 0.003 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.557 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.528 ±(99.9%) 0.467 ms/op [Average]
  (min, avg, max) = (2.512, 2.528, 2.557), stdev = 0.026
  CI (99.9%): [2.060, 2.995] (assumes normal distribution)


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
# Warmup Iteration   1: 4.936 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.066 ±(99.9%) 0.005 ms/op
Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
Iteration   3: 3.064 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.061 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (3.053, 3.061, 3.066), stdev = 0.007
  CI (99.9%): [2.928, 3.195] (assumes normal distribution)


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
# Warmup Iteration   1: 4.550 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.725 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.572 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  12.164 ms/op
                 createUser·p0.9999: 14.102 ms/op
                 createUser·p1.00:   14.909 ms/op

Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   4.157 ms/op
                 createUser·p0.999:  9.798 ms/op
                 createUser·p0.9999: 12.631 ms/op
                 createUser·p1.00:   12.943 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  8.429 ms/op
                 createUser·p0.9999: 9.983 ms/op
                 createUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375112
  mean =      2.557 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 175965 
    [ 2.500,  3.750) = 193714 
    [ 3.750,  5.000) = 4415 
    [ 5.000,  6.250) = 515 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      8.895 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.647 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.006 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  10.085 ms/op
                 existUser·p0.9999: 13.715 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.041 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.928 ms/op
                 existUser·p0.999:  6.215 ms/op
                 existUser·p0.9999: 14.505 ms/op
                 existUser·p1.00:   15.090 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.916 ms/op
                 existUser·p0.999:  8.831 ms/op
                 existUser·p0.9999: 10.867 ms/op
                 existUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385216
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 189067 
    [ 2.500,  3.750) = 191840 
    [ 3.750,  5.000) = 3200 
    [ 5.000,  6.250) = 601 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      7.156 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     14.938 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
Iteration   1: 2.530 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.090 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.006 ms/op
                 getUser·p0.999:  12.003 ms/op
                 getUser·p0.9999: 13.943 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.864 ms/op
                 getUser·p0.999:  9.510 ms/op
                 getUser·p0.9999: 14.991 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   3: 2.543 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  8.020 ms/op
                 getUser·p0.9999: 10.476 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378730
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 184881 
    [ 2.500,  3.750) = 187958 
    [ 3.750,  5.000) = 4261 
    [ 5.000,  6.250) = 1041 
    [ 6.250,  7.500) = 116 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.058 ms/op
     p(99.9000) =      8.241 ms/op
     p(99.9900) =     14.207 ms/op
     p(99.9990) =     15.275 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 4.809 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.009 ms/op
Iteration   1: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.918 ms/op
                 listUser·p0.9999: 11.420 ms/op
                 listUser·p1.00:   11.829 ms/op

Iteration   2: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 10.976 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   3: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 11.134 ms/op
                 listUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314384
  mean =      3.051 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 83912 
    [ 2.500,  3.750) = 189327 
    [ 3.750,  5.000) = 33595 
    [ 5.000,  6.250) = 6022 
    [ 6.250,  7.500) = 747 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 267 
    [10.000, 11.250) = 229 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     11.192 ms/op
     p(99.9990) =     11.761 ms/op
     p(99.9999) =     11.829 ms/op
    p(100.0000) =     11.829 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.716 ± 1.116  ops/ms
ClientPb.existUser                       thrpt       3  12.906 ± 0.181  ops/ms
ClientPb.getUser                         thrpt       3  12.575 ± 0.639  ops/ms
ClientPb.listUser                        thrpt       3  10.439 ± 1.583  ops/ms
ClientPb.createUser                       avgt       3   2.604 ± 0.513   ms/op
ClientPb.existUser                        avgt       3   2.496 ± 0.164   ms/op
ClientPb.getUser                          avgt       3   2.528 ± 0.467   ms/op
ClientPb.listUser                         avgt       3   3.061 ± 0.133   ms/op
ClientPb.createUser                     sample  375112   2.557 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.895           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.895           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.779           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.909           ms/op
ClientPb.existUser                      sample  385216   2.491 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.878           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.156           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.648           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.090           ms/op
ClientPb.getUser                        sample  378730   2.533 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.697           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.058           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.241           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.207           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.516           ms/op
ClientPb.listUser                       sample  314384   3.051 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.897           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.798           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.192           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.829           ms/op
