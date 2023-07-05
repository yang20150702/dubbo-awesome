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
# Warmup Iteration   1: 2.075 ops/ms
# Warmup Iteration   2: 4.854 ops/ms
# Warmup Iteration   3: 9.004 ops/ms
Iteration   1: 9.380 ops/ms
Iteration   2: 9.315 ops/ms
Iteration   3: 9.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.381 ±(99.9%) 1.218 ops/ms [Average]
  (min, avg, max) = (9.315, 9.381, 9.449), stdev = 0.067
  CI (99.9%): [8.163, 10.599] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.118 ops/ms
# Warmup Iteration   2: 8.872 ops/ms
# Warmup Iteration   3: 9.732 ops/ms
Iteration   1: 9.727 ops/ms
Iteration   2: 9.723 ops/ms
Iteration   3: 9.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.686 ±(99.9%) 1.243 ops/ms [Average]
  (min, avg, max) = (9.607, 9.686, 9.727), stdev = 0.068
  CI (99.9%): [8.443, 10.929] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.793 ops/ms
# Warmup Iteration   2: 8.642 ops/ms
# Warmup Iteration   3: 9.234 ops/ms
Iteration   1: 9.444 ops/ms
Iteration   2: 9.520 ops/ms
Iteration   3: 9.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.484 ±(99.9%) 0.696 ops/ms [Average]
  (min, avg, max) = (9.444, 9.484, 9.520), stdev = 0.038
  CI (99.9%): [8.787, 10.180] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.694 ops/ms
# Warmup Iteration   2: 7.285 ops/ms
# Warmup Iteration   3: 7.650 ops/ms
Iteration   1: 7.978 ops/ms
Iteration   2: 7.919 ops/ms
Iteration   3: 8.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.002 ±(99.9%) 1.782 ops/ms [Average]
  (min, avg, max) = (7.919, 8.002, 8.109), stdev = 0.098
  CI (99.9%): [6.220, 9.784] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.574 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.255 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.004 ms/op
Iteration   1: 3.506 ±(99.9%) 0.003 ms/op
Iteration   2: 3.333 ±(99.9%) 0.010 ms/op
Iteration   3: 3.473 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.437 ±(99.9%) 1.680 ms/op [Average]
  (min, avg, max) = (3.333, 3.437, 3.506), stdev = 0.092
  CI (99.9%): [1.757, 5.117] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.356 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.008 ms/op
Iteration   1: 3.367 ±(99.9%) 0.005 ms/op
Iteration   2: 3.338 ±(99.9%) 0.011 ms/op
Iteration   3: 3.273 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.326 ±(99.9%) 0.876 ms/op [Average]
  (min, avg, max) = (3.273, 3.326, 3.367), stdev = 0.048
  CI (99.9%): [2.450, 4.202] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 11.490 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.007 ms/op
Iteration   1: 3.558 ±(99.9%) 0.010 ms/op
Iteration   2: 3.538 ±(99.9%) 0.010 ms/op
Iteration   3: 3.556 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.550 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (3.538, 3.550, 3.558), stdev = 0.011
  CI (99.9%): [3.351, 3.750] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 12.401 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.603 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.014 ms/op
Iteration   1: 4.167 ±(99.9%) 0.005 ms/op
Iteration   2: 3.955 ±(99.9%) 0.014 ms/op
Iteration   3: 4.069 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.064 ±(99.9%) 1.936 ms/op [Average]
  (min, avg, max) = (3.955, 4.064, 4.167), stdev = 0.106
  CI (99.9%): [2.128, 5.999] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.250 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.010 ms/op
Iteration   1: 3.625 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.835 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   5.929 ms/op
                 createUser·p0.99:   7.643 ms/op
                 createUser·p0.999:  20.494 ms/op
                 createUser·p0.9999: 33.167 ms/op
                 createUser·p1.00:   34.079 ms/op

Iteration   2: 3.504 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.821 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  21.355 ms/op
                 createUser·p0.9999: 24.693 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   3: 3.538 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  19.669 ms/op
                 createUser·p0.9999: 28.310 ms/op
                 createUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269744
  mean =      3.555 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5529 
    [ 2.500,  5.000) = 254081 
    [ 5.000,  7.500) = 7971 
    [ 7.500, 10.000) = 1579 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.295 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     31.233 ms/op
     p(99.9990) =     33.494 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.122 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
Iteration   1: 3.199 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  11.862 ms/op
                 existUser·p0.9999: 20.021 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   2: 3.226 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  15.601 ms/op
                 existUser·p0.9999: 21.465 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   3: 3.275 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  13.250 ms/op
                 existUser·p0.9999: 23.658 ms/op
                 existUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296862
  mean =      3.233 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9302 
    [ 2.500,  5.000) = 281116 
    [ 5.000,  7.500) = 5652 
    [ 7.500, 10.000) = 362 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     14.702 ms/op
     p(99.9900) =     22.522 ms/op
     p(99.9990) =     24.124 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.855 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.010 ms/op
Iteration   1: 3.415 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.542 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  18.791 ms/op
                 getUser·p0.9999: 31.314 ms/op
                 getUser·p1.00:   32.047 ms/op

Iteration   2: 3.348 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.868 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  19.297 ms/op
                 getUser·p0.9999: 22.100 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   3: 3.331 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   2.060 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  17.702 ms/op
                 getUser·p0.9999: 26.621 ms/op
                 getUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285084
  mean =      3.364 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8799 
    [ 2.500,  5.000) = 268886 
    [ 5.000,  7.500) = 6223 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     30.408 ms/op
     p(99.9990) =     32.019 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.786 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.489 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.014 ms/op
Iteration   1: 4.029 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.825 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  20.137 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 3.965 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  15.679 ms/op
                 listUser·p0.9999: 17.595 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   3: 4.064 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  14.440 ms/op
                 listUser·p0.9999: 15.764 ms/op
                 listUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238680
  mean =      4.019 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 227050 
    [ 5.000,  7.500) = 9359 
    [ 7.500, 10.000) = 1371 
    [10.000, 12.500) = 352 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.825 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     15.679 ms/op
     p(99.9900) =     23.073 ms/op
     p(99.9990) =     24.084 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.381 ± 1.218  ops/ms
ClientPb.existUser                       thrpt       3   9.686 ± 1.243  ops/ms
ClientPb.getUser                         thrpt       3   9.484 ± 0.696  ops/ms
ClientPb.listUser                        thrpt       3   8.002 ± 1.782  ops/ms
ClientPb.createUser                       avgt       3   3.437 ± 1.680   ms/op
ClientPb.existUser                        avgt       3   3.326 ± 0.876   ms/op
ClientPb.getUser                          avgt       3   3.550 ± 0.199   ms/op
ClientPb.listUser                         avgt       3   4.064 ± 1.936   ms/op
ClientPb.createUser                     sample  269744   3.555 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.440           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.295           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.054           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.233           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.079           ms/op
ClientPb.existUser                      sample  296862   3.233 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.806           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.652           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.702           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.522           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.674           ms/op
ClientPb.getUser                        sample  285084   3.364 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.542           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.416           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.408           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.047           ms/op
ClientPb.listUser                       sample  238680   4.019 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.825           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.332           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.679           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.073           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.150           ms/op
