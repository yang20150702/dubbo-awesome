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
# Warmup Iteration   1: 1.113 ops/ms
# Warmup Iteration   2: 2.529 ops/ms
# Warmup Iteration   3: 5.171 ops/ms
Iteration   1: 5.842 ops/ms
Iteration   2: 5.947 ops/ms
Iteration   3: 6.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.006 ±(99.9%) 3.654 ops/ms [Average]
  (min, avg, max) = (5.842, 6.006, 6.229), stdev = 0.200
  CI (99.9%): [2.353, 9.660] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.793 ops/ms
# Warmup Iteration   2: 4.848 ops/ms
# Warmup Iteration   3: 6.583 ops/ms
Iteration   1: 6.555 ops/ms
Iteration   2: 6.505 ops/ms
Iteration   3: 6.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.485 ±(99.9%) 1.508 ops/ms [Average]
  (min, avg, max) = (6.394, 6.485, 6.555), stdev = 0.083
  CI (99.9%): [4.977, 7.992] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.797 ops/ms
# Warmup Iteration   2: 5.045 ops/ms
# Warmup Iteration   3: 6.177 ops/ms
Iteration   1: 6.050 ops/ms
Iteration   2: 6.229 ops/ms
Iteration   3: 6.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.248 ±(99.9%) 3.805 ops/ms [Average]
  (min, avg, max) = (6.050, 6.248, 6.466), stdev = 0.209
  CI (99.9%): [2.443, 10.053] (assumes normal distribution)


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
# Warmup Iteration   1: 1.797 ops/ms
# Warmup Iteration   2: 4.427 ops/ms
# Warmup Iteration   3: 5.148 ops/ms
Iteration   1: 5.247 ops/ms
Iteration   2: 5.113 ops/ms
Iteration   3: 5.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.240 ±(99.9%) 2.246 ops/ms [Average]
  (min, avg, max) = (5.113, 5.240, 5.359), stdev = 0.123
  CI (99.9%): [2.994, 7.486] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 16.820 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.275 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.506 ±(99.9%) 0.014 ms/op
Iteration   1: 5.397 ±(99.9%) 0.013 ms/op
Iteration   2: 5.302 ±(99.9%) 0.010 ms/op
Iteration   3: 5.118 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.272 ±(99.9%) 2.587 ms/op [Average]
  (min, avg, max) = (5.118, 5.272, 5.397), stdev = 0.142
  CI (99.9%): [2.685, 7.859] (assumes normal distribution)


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
# Warmup Iteration   1: 16.194 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.913 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.996 ±(99.9%) 0.014 ms/op
Iteration   1: 4.920 ±(99.9%) 0.009 ms/op
Iteration   2: 4.844 ±(99.9%) 0.008 ms/op
Iteration   3: 4.943 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.902 ±(99.9%) 0.948 ms/op [Average]
  (min, avg, max) = (4.844, 4.902, 4.943), stdev = 0.052
  CI (99.9%): [3.955, 5.850] (assumes normal distribution)


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
# Warmup Iteration   1: 16.273 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.006 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.343 ±(99.9%) 0.006 ms/op
Iteration   1: 5.243 ±(99.9%) 0.010 ms/op
Iteration   2: 5.174 ±(99.9%) 0.010 ms/op
Iteration   3: 5.226 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.214 ±(99.9%) 0.657 ms/op [Average]
  (min, avg, max) = (5.174, 5.214, 5.243), stdev = 0.036
  CI (99.9%): [4.557, 5.871] (assumes normal distribution)


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
# Warmup Iteration   1: 19.258 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.193 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.165 ±(99.9%) 0.013 ms/op
Iteration   1: 6.133 ±(99.9%) 0.011 ms/op
Iteration   2: 6.099 ±(99.9%) 0.011 ms/op
Iteration   3: 6.054 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.095 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (6.054, 6.095, 6.133), stdev = 0.040
  CI (99.9%): [5.375, 6.816] (assumes normal distribution)


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
# Warmup Iteration   1: 16.511 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 6.257 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.734 ±(99.9%) 0.026 ms/op
Iteration   1: 5.309 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.540 ms/op
                 createUser·p0.50:   5.063 ms/op
                 createUser·p0.90:   6.291 ms/op
                 createUser·p0.95:   7.602 ms/op
                 createUser·p0.99:   10.662 ms/op
                 createUser·p0.999:  23.104 ms/op
                 createUser·p0.9999: 29.945 ms/op
                 createUser·p1.00:   30.441 ms/op

Iteration   2: 5.300 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.524 ms/op
                 createUser·p0.50:   5.063 ms/op
                 createUser·p0.90:   6.324 ms/op
                 createUser·p0.95:   7.143 ms/op
                 createUser·p0.99:   10.076 ms/op
                 createUser·p0.999:  22.665 ms/op
                 createUser·p0.9999: 27.623 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   3: 5.213 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.200 ms/op
                 createUser·p0.50:   4.964 ms/op
                 createUser·p0.90:   6.210 ms/op
                 createUser·p0.95:   7.062 ms/op
                 createUser·p0.99:   9.859 ms/op
                 createUser·p0.999:  23.889 ms/op
                 createUser·p0.9999: 27.886 ms/op
                 createUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182090
  mean =      5.274 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 87327 
    [ 5.000,  7.500) = 86647 
    [ 7.500, 10.000) = 6056 
    [10.000, 12.500) = 1408 
    [12.500, 15.000) = 272 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.275 ms/op
     p(95.0000) =      7.258 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     22.967 ms/op
     p(99.9900) =     27.911 ms/op
     p(99.9990) =     30.388 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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
# Warmup Iteration   1: 16.279 ±(99.9%) 0.270 ms/op
# Warmup Iteration   2: 6.042 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.083 ±(99.9%) 0.019 ms/op
Iteration   1: 4.917 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.011 ms/op
                 existUser·p0.50:   4.678 ms/op
                 existUser·p0.90:   5.923 ms/op
                 existUser·p0.95:   6.791 ms/op
                 existUser·p0.99:   8.667 ms/op
                 existUser·p0.999:  14.594 ms/op
                 existUser·p0.9999: 27.295 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   2: 4.931 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.494 ms/op
                 existUser·p0.50:   4.694 ms/op
                 existUser·p0.90:   5.988 ms/op
                 existUser·p0.95:   7.045 ms/op
                 existUser·p0.99:   9.732 ms/op
                 existUser·p0.999:  18.478 ms/op
                 existUser·p0.9999: 28.836 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   3: 4.874 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.273 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   5.693 ms/op
                 existUser·p0.95:   6.463 ms/op
                 existUser·p0.99:   9.339 ms/op
                 existUser·p0.999:  18.847 ms/op
                 existUser·p0.9999: 30.456 ms/op
                 existUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 195592
  mean =      4.907 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 141663 
    [ 5.000,  7.500) = 47642 
    [ 7.500, 10.000) = 4859 
    [10.000, 12.500) = 780 
    [12.500, 15.000) = 341 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.011 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.849 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =      9.191 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     29.375 ms/op
     p(99.9990) =     30.934 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 15.845 ±(99.9%) 0.258 ms/op
# Warmup Iteration   2: 5.994 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.389 ±(99.9%) 0.018 ms/op
Iteration   1: 5.195 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.306 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.119 ms/op
                 getUser·p0.95:   7.602 ms/op
                 getUser·p0.99:   11.868 ms/op
                 getUser·p0.999:  21.249 ms/op
                 getUser·p0.9999: 25.282 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   2: 5.189 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.458 ms/op
                 getUser·p0.50:   4.964 ms/op
                 getUser·p0.90:   6.218 ms/op
                 getUser·p0.95:   6.939 ms/op
                 getUser·p0.99:   9.634 ms/op
                 getUser·p0.999:  22.850 ms/op
                 getUser·p0.9999: 29.409 ms/op
                 getUser·p1.00:   30.114 ms/op

Iteration   3: 5.065 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.970 ms/op
                 getUser·p0.50:   4.850 ms/op
                 getUser·p0.90:   5.939 ms/op
                 getUser·p0.95:   6.627 ms/op
                 getUser·p0.99:   9.798 ms/op
                 getUser·p0.999:  24.801 ms/op
                 getUser·p0.9999: 31.842 ms/op
                 getUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 186254
  mean =      5.149 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 107290 
    [ 5.000,  7.500) = 71906 
    [ 7.500, 10.000) = 4886 
    [10.000, 12.500) = 1257 
    [12.500, 15.000) = 511 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.306 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      6.103 ms/op
     p(95.0000) =      6.949 ms/op
     p(99.0000) =     10.322 ms/op
     p(99.9000) =     23.028 ms/op
     p(99.9900) =     30.687 ms/op
     p(99.9990) =     32.154 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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
# Warmup Iteration   1: 19.560 ±(99.9%) 0.335 ms/op
# Warmup Iteration   2: 7.203 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.257 ±(99.9%) 0.023 ms/op
Iteration   1: 6.208 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   5.874 ms/op
                 listUser·p0.90:   7.283 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   12.452 ms/op
                 listUser·p0.999:  24.494 ms/op
                 listUser·p0.9999: 27.684 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 6.234 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.679 ms/op
                 listUser·p0.50:   5.865 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   12.747 ms/op
                 listUser·p0.999:  27.263 ms/op
                 listUser·p0.9999: 29.814 ms/op
                 listUser·p1.00:   37.880 ms/op

Iteration   3: 6.068 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.675 ms/op
                 listUser·p0.50:   5.808 ms/op
                 listUser·p0.90:   7.053 ms/op
                 listUser·p0.95:   7.954 ms/op
                 listUser·p0.99:   11.193 ms/op
                 listUser·p0.999:  22.160 ms/op
                 listUser·p0.9999: 25.845 ms/op
                 listUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155626
  mean =      6.169 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 9156 
    [ 5.000,  7.500) = 133347 
    [ 7.500, 10.000) = 9115 
    [10.000, 12.500) = 2631 
    [12.500, 15.000) = 784 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      5.849 ms/op
     p(90.0000) =      7.250 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     12.206 ms/op
     p(99.9000) =     24.719 ms/op
     p(99.9900) =     29.061 ms/op
     p(99.9990) =     33.505 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.006 ± 3.654  ops/ms
ClientPb.existUser                       thrpt       3   6.485 ± 1.508  ops/ms
ClientPb.getUser                         thrpt       3   6.248 ± 3.805  ops/ms
ClientPb.listUser                        thrpt       3   5.240 ± 2.246  ops/ms
ClientPb.createUser                       avgt       3   5.272 ± 2.587   ms/op
ClientPb.existUser                        avgt       3   4.902 ± 0.948   ms/op
ClientPb.getUser                          avgt       3   5.214 ± 0.657   ms/op
ClientPb.listUser                         avgt       3   6.095 ± 0.721   ms/op
ClientPb.createUser                     sample  182090   5.274 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.524           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.030           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.275           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.258           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.224           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.967           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.911           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.441           ms/op
ClientPb.existUser                      sample  195592   4.907 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.011           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.849           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.791           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.191           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.908           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.375           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.966           ms/op
ClientPb.getUser                        sample  186254   5.149 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.306           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.891           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.103           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.949           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.322           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.028           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.687           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.211           ms/op
ClientPb.listUser                       sample  155626   6.169 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.264           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.849           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.250           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.206           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.719           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.061           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.880           ms/op
