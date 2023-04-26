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
# Warmup Iteration   1: 1.819 ops/ms
# Warmup Iteration   2: 3.880 ops/ms
# Warmup Iteration   3: 7.253 ops/ms
Iteration   1: 7.321 ops/ms
Iteration   2: 8.004 ops/ms
Iteration   3: 6.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.330 ±(99.9%) 12.198 ops/ms [Average]
  (min, avg, max) = (6.667, 7.330, 8.004), stdev = 0.669
  CI (99.9%): [≈ 0, 19.528] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.224 ops/ms
# Warmup Iteration   2: 6.043 ops/ms
# Warmup Iteration   3: 7.599 ops/ms
Iteration   1: 8.150 ops/ms
Iteration   2: 8.110 ops/ms
Iteration   3: 8.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.107 ±(99.9%) 0.813 ops/ms [Average]
  (min, avg, max) = (8.061, 8.107, 8.150), stdev = 0.045
  CI (99.9%): [7.294, 8.920] (assumes normal distribution)


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
# Warmup Iteration   1: 2.183 ops/ms
# Warmup Iteration   2: 6.795 ops/ms
# Warmup Iteration   3: 7.657 ops/ms
Iteration   1: 7.773 ops/ms
Iteration   2: 7.791 ops/ms
Iteration   3: 7.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.817 ±(99.9%) 1.124 ops/ms [Average]
  (min, avg, max) = (7.773, 7.817, 7.887), stdev = 0.062
  CI (99.9%): [6.693, 8.941] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.030 ops/ms
# Warmup Iteration   2: 5.407 ops/ms
# Warmup Iteration   3: 6.626 ops/ms
Iteration   1: 6.557 ops/ms
Iteration   2: 6.665 ops/ms
Iteration   3: 6.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.620 ±(99.9%) 1.021 ops/ms [Average]
  (min, avg, max) = (6.557, 6.620, 6.665), stdev = 0.056
  CI (99.9%): [5.599, 7.640] (assumes normal distribution)


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
# Warmup Iteration   1: 14.454 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.750 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.008 ms/op
Iteration   1: 4.075 ±(99.9%) 0.005 ms/op
Iteration   2: 4.112 ±(99.9%) 0.008 ms/op
Iteration   3: 4.088 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.092 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (4.075, 4.092, 4.112), stdev = 0.019
  CI (99.9%): [3.750, 4.434] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.964 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.249 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.006 ms/op
Iteration   1: 3.927 ±(99.9%) 0.007 ms/op
Iteration   2: 3.873 ±(99.9%) 0.006 ms/op
Iteration   3: 3.971 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.924 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (3.873, 3.924, 3.971), stdev = 0.049
  CI (99.9%): [3.027, 4.821] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.898 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.007 ms/op
Iteration   1: 4.120 ±(99.9%) 0.006 ms/op
Iteration   2: 3.992 ±(99.9%) 0.006 ms/op
Iteration   3: 3.884 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.999 ±(99.9%) 2.157 ms/op [Average]
  (min, avg, max) = (3.884, 3.999, 4.120), stdev = 0.118
  CI (99.9%): [1.842, 6.156] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.238 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.301 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.999 ±(99.9%) 0.008 ms/op
Iteration   1: 4.790 ±(99.9%) 0.010 ms/op
Iteration   2: 4.807 ±(99.9%) 0.010 ms/op
Iteration   3: 4.710 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.769 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (4.710, 4.769, 4.807), stdev = 0.052
  CI (99.9%): [3.819, 5.718] (assumes normal distribution)


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
# Warmup Iteration   1: 13.017 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.678 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.417 ±(99.9%) 0.020 ms/op
Iteration   1: 4.025 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   8.547 ms/op
                 createUser·p0.999:  25.053 ms/op
                 createUser·p0.9999: 29.236 ms/op
                 createUser·p1.00:   30.343 ms/op

Iteration   2: 3.993 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   5.767 ms/op
                 createUser·p0.99:   8.172 ms/op
                 createUser·p0.999:  26.603 ms/op
                 createUser·p0.9999: 34.865 ms/op
                 createUser·p1.00:   36.110 ms/op

Iteration   3: 4.101 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   5.104 ms/op
                 createUser·p0.95:   6.267 ms/op
                 createUser·p0.99:   8.431 ms/op
                 createUser·p0.999:  14.464 ms/op
                 createUser·p0.9999: 35.389 ms/op
                 createUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237623
  mean =      4.039 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1295 
    [ 2.500,  5.000) = 213304 
    [ 5.000,  7.500) = 18575 
    [ 7.500, 10.000) = 3396 
    [10.000, 12.500) = 567 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 115 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 45 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     25.100 ms/op
     p(99.9900) =     34.800 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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
# Warmup Iteration   1: 12.297 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.406 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.015 ms/op
Iteration   1: 4.022 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.884 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   6.185 ms/op
                 existUser·p0.99:   8.364 ms/op
                 existUser·p0.999:  12.222 ms/op
                 existUser·p0.9999: 22.911 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   2: 3.976 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.997 ms/op
                 existUser·p0.95:   5.923 ms/op
                 existUser·p0.99:   8.059 ms/op
                 existUser·p0.999:  22.062 ms/op
                 existUser·p0.9999: 27.119 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   3: 4.037 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.855 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   6.062 ms/op
                 existUser·p0.99:   8.200 ms/op
                 existUser·p0.999:  15.401 ms/op
                 existUser·p0.9999: 28.284 ms/op
                 existUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 239132
  mean =      4.011 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1613 
    [ 2.500,  5.000) = 212685 
    [ 5.000,  7.500) = 20813 
    [ 7.500, 10.000) = 3124 
    [10.000, 12.500) = 586 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 84 

  Percentiles, ms/op:
      p(0.0000) =      1.245 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      6.078 ms/op
     p(99.0000) =      8.208 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     27.361 ms/op
     p(99.9990) =     29.114 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 11.507 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.654 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.199 ±(99.9%) 0.017 ms/op
Iteration   1: 4.092 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.927 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   5.120 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  22.802 ms/op
                 getUser·p0.9999: 26.876 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   2: 4.154 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   6.775 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  13.443 ms/op
                 getUser·p0.9999: 27.306 ms/op
                 getUser·p1.00:   29.295 ms/op

Iteration   3: 4.155 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   5.071 ms/op
                 getUser·p0.95:   6.260 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  28.738 ms/op
                 getUser·p0.9999: 32.090 ms/op
                 getUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232068
  mean =      4.134 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1093 
    [ 2.500,  5.000) = 204316 
    [ 5.000,  7.500) = 20954 
    [ 7.500, 10.000) = 4757 
    [10.000, 12.500) = 583 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      6.332 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     23.261 ms/op
     p(99.9900) =     30.926 ms/op
     p(99.9990) =     33.014 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 15.019 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 5.387 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.773 ±(99.9%) 0.019 ms/op
Iteration   1: 4.783 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   7.307 ms/op
                 listUser·p0.99:   9.969 ms/op
                 listUser·p0.999:  24.047 ms/op
                 listUser·p0.9999: 26.880 ms/op
                 listUser·p1.00:   28.213 ms/op

Iteration   2: 4.739 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   7.225 ms/op
                 listUser·p0.99:   9.868 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 22.897 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   3: 4.736 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.661 ms/op
                 listUser·p0.95:   6.898 ms/op
                 listUser·p0.99:   9.503 ms/op
                 listUser·p0.999:  19.464 ms/op
                 listUser·p0.9999: 24.871 ms/op
                 listUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201911
  mean =      4.753 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 161477 
    [ 5.000,  7.500) = 32315 
    [ 7.500, 10.000) = 6254 
    [10.000, 12.500) = 1118 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.767 ms/op
     p(95.0000) =      7.152 ms/op
     p(99.0000) =      9.796 ms/op
     p(99.9000) =     20.450 ms/op
     p(99.9900) =     26.274 ms/op
     p(99.9990) =     27.291 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.330 ± 12.198  ops/ms
ClientPb.existUser                       thrpt       3   8.107 ±  0.813  ops/ms
ClientPb.getUser                         thrpt       3   7.817 ±  1.124  ops/ms
ClientPb.listUser                        thrpt       3   6.620 ±  1.021  ops/ms
ClientPb.createUser                       avgt       3   4.092 ±  0.342   ms/op
ClientPb.existUser                        avgt       3   3.924 ±  0.897   ms/op
ClientPb.getUser                          avgt       3   3.999 ±  2.157   ms/op
ClientPb.listUser                         avgt       3   4.769 ±  0.949   ms/op
ClientPb.createUser                     sample  237623   4.039 ±  0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.253            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.768            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.964            ms/op
ClientPb.createUser:createUser·p0.95    sample           6.046            ms/op
ClientPb.createUser:createUser·p0.99    sample           8.389            ms/op
ClientPb.createUser:createUser·p0.999   sample          25.100            ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.800            ms/op
ClientPb.createUser:createUser·p1.00    sample          36.110            ms/op
ClientPb.existUser                      sample  239132   4.011 ±  0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.245            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.748            ms/op
ClientPb.existUser:existUser·p0.90      sample           5.054            ms/op
ClientPb.existUser:existUser·p0.95      sample           6.078            ms/op
ClientPb.existUser:existUser·p0.99      sample           8.208            ms/op
ClientPb.existUser:existUser·p0.999     sample          15.401            ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.361            ms/op
ClientPb.existUser:existUser·p1.00      sample          29.327            ms/op
ClientPb.getUser                        sample  232068   4.134 ±  0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.356            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.850            ms/op
ClientPb.getUser:getUser·p0.90          sample           5.194            ms/op
ClientPb.getUser:getUser·p0.95          sample           6.332            ms/op
ClientPb.getUser:getUser·p0.99          sample           8.585            ms/op
ClientPb.getUser:getUser·p0.999         sample          23.261            ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.926            ms/op
ClientPb.getUser:getUser·p1.00          sample          33.456            ms/op
ClientPb.listUser                       sample  201911   4.753 ±  0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.998            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.440            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.767            ms/op
ClientPb.listUser:listUser·p0.95        sample           7.152            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.796            ms/op
ClientPb.listUser:listUser·p0.999       sample          20.450            ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.274            ms/op
ClientPb.listUser:listUser·p1.00        sample          28.213            ms/op
