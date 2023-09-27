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
# Warmup Iteration   1: 1.752 ops/ms
# Warmup Iteration   2: 3.741 ops/ms
# Warmup Iteration   3: 7.353 ops/ms
Iteration   1: 7.729 ops/ms
Iteration   2: 7.917 ops/ms
Iteration   3: 7.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.864 ±(99.9%) 2.164 ops/ms [Average]
  (min, avg, max) = (7.729, 7.864, 7.948), stdev = 0.119
  CI (99.9%): [5.700, 10.029] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.220 ops/ms
# Warmup Iteration   2: 7.113 ops/ms
# Warmup Iteration   3: 8.041 ops/ms
Iteration   1: 8.032 ops/ms
Iteration   2: 8.188 ops/ms
Iteration   3: 8.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.216 ±(99.9%) 3.633 ops/ms [Average]
  (min, avg, max) = (8.032, 8.216, 8.427), stdev = 0.199
  CI (99.9%): [4.583, 11.848] (assumes normal distribution)


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
# Warmup Iteration   1: 2.194 ops/ms
# Warmup Iteration   2: 6.428 ops/ms
# Warmup Iteration   3: 7.795 ops/ms
Iteration   1: 7.598 ops/ms
Iteration   2: 7.968 ops/ms
Iteration   3: 8.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.869 ±(99.9%) 4.325 ops/ms [Average]
  (min, avg, max) = (7.598, 7.869, 8.040), stdev = 0.237
  CI (99.9%): [3.544, 12.194] (assumes normal distribution)


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
# Warmup Iteration   1: 2.149 ops/ms
# Warmup Iteration   2: 5.945 ops/ms
# Warmup Iteration   3: 6.481 ops/ms
Iteration   1: 6.494 ops/ms
Iteration   2: 6.766 ops/ms
Iteration   3: 6.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.714 ±(99.9%) 3.647 ops/ms [Average]
  (min, avg, max) = (6.494, 6.714, 6.883), stdev = 0.200
  CI (99.9%): [3.067, 10.362] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.393 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.006 ms/op
Iteration   1: 4.028 ±(99.9%) 0.005 ms/op
Iteration   2: 3.992 ±(99.9%) 0.005 ms/op
Iteration   3: 3.999 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.006 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (3.992, 4.006, 4.028), stdev = 0.019
  CI (99.9%): [3.658, 4.354] (assumes normal distribution)


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
# Warmup Iteration   1: 12.429 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.003 ms/op
Iteration   1: 3.761 ±(99.9%) 0.002 ms/op
Iteration   2: 3.731 ±(99.9%) 0.003 ms/op
Iteration   3: 3.809 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.767 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (3.731, 3.767, 3.809), stdev = 0.040
  CI (99.9%): [3.040, 4.494] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.548 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.624 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.004 ms/op
Iteration   1: 3.926 ±(99.9%) 0.005 ms/op
Iteration   2: 3.929 ±(99.9%) 0.003 ms/op
Iteration   3: 3.911 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.922 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (3.911, 3.922, 3.929), stdev = 0.010
  CI (99.9%): [3.748, 4.095] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 12.711 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.217 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.917 ±(99.9%) 0.006 ms/op
Iteration   1: 4.649 ±(99.9%) 0.006 ms/op
Iteration   2: 4.726 ±(99.9%) 0.007 ms/op
Iteration   3: 4.642 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.672 ±(99.9%) 0.848 ms/op [Average]
  (min, avg, max) = (4.642, 4.672, 4.726), stdev = 0.046
  CI (99.9%): [3.824, 5.520] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.160 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.970 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.017 ms/op
Iteration   1: 3.998 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.194 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   7.717 ms/op
                 createUser·p0.999:  22.968 ms/op
                 createUser·p0.9999: 25.362 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   2: 4.030 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.554 ms/op
                 createUser·p0.999:  15.503 ms/op
                 createUser·p0.9999: 25.827 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   3: 3.995 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  26.542 ms/op
                 createUser·p0.9999: 29.327 ms/op
                 createUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239466
  mean =      4.008 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 495 
    [ 2.500,  5.000) = 228469 
    [ 5.000,  7.500) = 8657 
    [ 7.500, 10.000) = 1245 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.031 ms/op
     p(99.9000) =     22.970 ms/op
     p(99.9900) =     28.286 ms/op
     p(99.9990) =     29.944 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 10.735 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.012 ms/op
Iteration   1: 3.869 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.901 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.889 ms/op
                 existUser·p0.999:  21.995 ms/op
                 existUser·p0.9999: 25.570 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   2: 3.851 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   7.766 ms/op
                 existUser·p0.999:  14.762 ms/op
                 existUser·p0.9999: 27.974 ms/op
                 existUser·p1.00:   29.327 ms/op

Iteration   3: 3.835 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.554 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   7.430 ms/op
                 existUser·p0.999:  25.002 ms/op
                 existUser·p0.9999: 29.524 ms/op
                 existUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249275
  mean =      3.851 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 425 
    [ 2.500,  5.000) = 239821 
    [ 5.000,  7.500) = 6674 
    [ 7.500, 10.000) = 1519 
    [10.000, 12.500) = 461 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     21.677 ms/op
     p(99.9900) =     28.639 ms/op
     p(99.9990) =     30.245 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 12.088 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.498 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.018 ms/op
Iteration   1: 4.081 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.232 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   8.077 ms/op
                 getUser·p0.999:  27.296 ms/op
                 getUser·p0.9999: 30.512 ms/op
                 getUser·p1.00:   31.261 ms/op

Iteration   2: 3.978 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.516 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  25.012 ms/op
                 getUser·p0.9999: 27.820 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   3: 3.973 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  10.371 ms/op
                 getUser·p0.9999: 30.438 ms/op
                 getUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239200
  mean =      4.010 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 228669 
    [ 5.000,  7.500) = 7764 
    [ 7.500, 10.000) = 2084 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 124 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     25.061 ms/op
     p(99.9900) =     30.313 ms/op
     p(99.9990) =     31.026 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 13.463 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 5.677 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.886 ±(99.9%) 0.015 ms/op
Iteration   1: 4.857 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   8.369 ms/op
                 listUser·p0.999:  22.940 ms/op
                 listUser·p0.9999: 24.996 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   2: 4.850 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   9.145 ms/op
                 listUser·p0.999:  17.086 ms/op
                 listUser·p0.9999: 20.981 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   3: 4.727 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  15.860 ms/op
                 listUser·p0.9999: 18.686 ms/op
                 listUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199433
  mean =      4.811 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 156787 
    [ 5.000,  7.500) = 39060 
    [ 7.500, 10.000) = 2467 
    [10.000, 12.500) = 482 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 278 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     24.609 ms/op
     p(99.9990) =     25.593 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.864 ± 2.164  ops/ms
ClientPb.existUser                       thrpt       3   8.216 ± 3.633  ops/ms
ClientPb.getUser                         thrpt       3   7.869 ± 4.325  ops/ms
ClientPb.listUser                        thrpt       3   6.714 ± 3.647  ops/ms
ClientPb.createUser                       avgt       3   4.006 ± 0.348   ms/op
ClientPb.existUser                        avgt       3   3.767 ± 0.727   ms/op
ClientPb.getUser                          avgt       3   3.922 ± 0.174   ms/op
ClientPb.listUser                         avgt       3   4.672 ± 0.848   ms/op
ClientPb.createUser                     sample  239466   4.008 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.194           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.940           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.031           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.970           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.286           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.114           ms/op
ClientPb.existUser                      sample  249275   3.851 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.403           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.710           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.397           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.677           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.639           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.671           ms/op
ClientPb.getUser                        sample  239200   4.010 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.311           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.858           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.717           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.061           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.313           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.261           ms/op
ClientPb.listUser                       sample  199433   4.811 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.530           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.259           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.405           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.793           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.609           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.756           ms/op
