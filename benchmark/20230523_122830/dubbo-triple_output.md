# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.556 ops/ms
# Warmup Iteration   2: 3.871 ops/ms
# Warmup Iteration   3: 7.217 ops/ms
Iteration   1: 7.371 ops/ms
Iteration   2: 8.119 ops/ms
Iteration   3: 8.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.834 ±(99.9%) 7.384 ops/ms [Average]
  (min, avg, max) = (7.371, 7.834, 8.119), stdev = 0.405
  CI (99.9%): [0.451, 15.218] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.386 ops/ms
# Warmup Iteration   2: 7.600 ops/ms
# Warmup Iteration   3: 8.594 ops/ms
Iteration   1: 8.170 ops/ms
Iteration   2: 8.608 ops/ms
Iteration   3: 8.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.444 ±(99.9%) 4.359 ops/ms [Average]
  (min, avg, max) = (8.170, 8.444, 8.608), stdev = 0.239
  CI (99.9%): [4.085, 12.803] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.031 ops/ms
# Warmup Iteration   2: 6.623 ops/ms
# Warmup Iteration   3: 7.614 ops/ms
Iteration   1: 7.987 ops/ms
Iteration   2: 7.758 ops/ms
Iteration   3: 8.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.915 ±(99.9%) 2.484 ops/ms [Average]
  (min, avg, max) = (7.758, 7.915, 8.000), stdev = 0.136
  CI (99.9%): [5.431, 10.399] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.058 ops/ms
# Warmup Iteration   2: 6.067 ops/ms
# Warmup Iteration   3: 6.785 ops/ms
Iteration   1: 7.040 ops/ms
Iteration   2: 7.071 ops/ms
Iteration   3: 6.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.905 ±(99.9%) 4.764 ops/ms [Average]
  (min, avg, max) = (6.604, 6.905, 7.071), stdev = 0.261
  CI (99.9%): [2.142, 11.669] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 11.187 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.010 ms/op
Iteration   1: 3.926 ±(99.9%) 0.008 ms/op
Iteration   2: 3.929 ±(99.9%) 0.007 ms/op
Iteration   3: 3.870 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.908 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (3.870, 3.908, 3.929), stdev = 0.033
  CI (99.9%): [3.310, 4.507] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.891 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.004 ms/op
Iteration   1: 3.793 ±(99.9%) 0.012 ms/op
Iteration   2: 3.832 ±(99.9%) 0.006 ms/op
Iteration   3: 3.767 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.797 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (3.767, 3.797, 3.832), stdev = 0.033
  CI (99.9%): [3.201, 4.393] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 11.835 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.517 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.008 ms/op
Iteration   1: 3.950 ±(99.9%) 0.008 ms/op
Iteration   2: 3.809 ±(99.9%) 0.008 ms/op
Iteration   3: 4.125 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.962 ±(99.9%) 2.890 ms/op [Average]
  (min, avg, max) = (3.809, 3.962, 4.125), stdev = 0.158
  CI (99.9%): [1.072, 6.851] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 14.326 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.041 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.715 ±(99.9%) 0.008 ms/op
Iteration   1: 4.680 ±(99.9%) 0.008 ms/op
Iteration   2: 4.447 ±(99.9%) 0.016 ms/op
Iteration   3: 4.678 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.602 ±(99.9%) 2.450 ms/op [Average]
  (min, avg, max) = (4.447, 4.602, 4.680), stdev = 0.134
  CI (99.9%): [2.152, 7.052] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.027 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 5.315 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.460 ±(99.9%) 0.019 ms/op
Iteration   1: 4.068 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   7.610 ms/op
                 createUser·p0.999:  24.589 ms/op
                 createUser·p0.9999: 42.795 ms/op
                 createUser·p1.00:   43.647 ms/op

Iteration   2: 3.870 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.593 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  19.870 ms/op
                 createUser·p0.9999: 27.353 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   3: 3.995 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.554 ms/op
                 createUser·p0.99:   7.840 ms/op
                 createUser·p0.999:  27.754 ms/op
                 createUser·p0.9999: 34.208 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241338
  mean =      3.976 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 227559 
    [ 5.000, 10.000) = 13123 
    [10.000, 15.000) = 256 
    [15.000, 20.000) = 118 
    [20.000, 25.000) = 45 
    [25.000, 30.000) = 155 
    [30.000, 35.000) = 50 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     24.652 ms/op
     p(99.9900) =     41.746 ms/op
     p(99.9990) =     43.188 ms/op
     p(99.9999) =     43.647 ms/op
    p(100.0000) =     43.647 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 11.564 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.428 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.924 ±(99.9%) 0.012 ms/op
Iteration   1: 3.751 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   6.431 ms/op
                 existUser·p0.999:  22.544 ms/op
                 existUser·p0.9999: 25.199 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   2: 3.796 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  9.814 ms/op
                 existUser·p0.9999: 26.384 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   3: 3.737 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.782 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.672 ms/op
                 existUser·p0.999:  26.367 ms/op
                 existUser·p0.9999: 30.030 ms/op
                 existUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254989
  mean =      3.761 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 214 
    [ 2.500,  5.000) = 246890 
    [ 5.000,  7.500) = 6435 
    [ 7.500, 10.000) = 828 
    [10.000, 12.500) = 344 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     21.727 ms/op
     p(99.9900) =     29.327 ms/op
     p(99.9990) =     30.700 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.542 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 4.599 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.011 ms/op
Iteration   1: 3.976 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   7.561 ms/op
                 getUser·p0.999:  22.891 ms/op
                 getUser·p0.9999: 29.125 ms/op
                 getUser·p1.00:   30.933 ms/op

Iteration   2: 3.847 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.050 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  11.038 ms/op
                 getUser·p0.9999: 28.685 ms/op
                 getUser·p1.00:   29.786 ms/op

Iteration   3: 3.787 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.015 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.493 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  25.309 ms/op
                 getUser·p0.9999: 29.018 ms/op
                 getUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 247925
  mean =      3.868 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 241014 
    [ 5.000,  7.500) = 5042 
    [ 7.500, 10.000) = 1207 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     22.645 ms/op
     p(99.9900) =     28.948 ms/op
     p(99.9990) =     30.692 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.006 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 5.575 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.765 ±(99.9%) 0.018 ms/op
Iteration   1: 4.581 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  23.822 ms/op
                 listUser·p0.9999: 27.559 ms/op
                 listUser·p1.00:   28.672 ms/op

Iteration   2: 4.754 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   8.967 ms/op
                 listUser·p0.999:  21.258 ms/op
                 listUser·p0.9999: 26.658 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   3: 4.678 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  19.255 ms/op
                 listUser·p0.9999: 22.828 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205428
  mean =      4.670 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 171837 
    [ 5.000,  7.500) = 28773 
    [ 7.500, 10.000) = 3846 
    [10.000, 12.500) = 404 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      2.001 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     21.552 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     27.720 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.834 ± 7.384  ops/ms
ClientPb.existUser                       thrpt       3   8.444 ± 4.359  ops/ms
ClientPb.getUser                         thrpt       3   7.915 ± 2.484  ops/ms
ClientPb.listUser                        thrpt       3   6.905 ± 4.764  ops/ms
ClientPb.createUser                       avgt       3   3.908 ± 0.598   ms/op
ClientPb.existUser                        avgt       3   3.797 ± 0.596   ms/op
ClientPb.getUser                          avgt       3   3.962 ± 2.890   ms/op
ClientPb.listUser                         avgt       3   4.602 ± 2.450   ms/op
ClientPb.createUser                     sample  241338   3.976 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.300           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.397           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.652           ms/op
ClientPb.createUser:createUser·p0.9999  sample          41.746           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.647           ms/op
ClientPb.existUser                      sample  254989   3.761 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.153           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.129           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.522           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.488           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.727           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.327           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.195           ms/op
ClientPb.getUser                        sample  247925   3.868 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.380           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.555           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.889           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.645           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.948           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.933           ms/op
ClientPb.listUser                       sample  205428   4.670 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.001           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.552           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.706           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.672           ms/op
