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
# Warmup Iteration   1: 1.739 ops/ms
# Warmup Iteration   2: 3.619 ops/ms
# Warmup Iteration   3: 7.053 ops/ms
Iteration   1: 7.583 ops/ms
Iteration   2: 7.752 ops/ms
Iteration   3: 7.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.763 ±(99.9%) 3.407 ops/ms [Average]
  (min, avg, max) = (7.583, 7.763, 7.956), stdev = 0.187
  CI (99.9%): [4.356, 11.171] (assumes normal distribution)


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
# Warmup Iteration   1: 2.224 ops/ms
# Warmup Iteration   2: 6.201 ops/ms
# Warmup Iteration   3: 7.146 ops/ms
Iteration   1: 7.214 ops/ms
Iteration   2: 7.309 ops/ms
Iteration   3: 7.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.401 ±(99.9%) 4.511 ops/ms [Average]
  (min, avg, max) = (7.214, 7.401, 7.681), stdev = 0.247
  CI (99.9%): [2.891, 11.912] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.826 ops/ms
# Warmup Iteration   2: 4.607 ops/ms
# Warmup Iteration   3: 6.982 ops/ms
Iteration   1: 6.963 ops/ms
Iteration   2: 7.112 ops/ms
Iteration   3: 7.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.029 ±(99.9%) 1.385 ops/ms [Average]
  (min, avg, max) = (6.963, 7.029, 7.112), stdev = 0.076
  CI (99.9%): [5.644, 8.414] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.815 ops/ms
# Warmup Iteration   2: 5.034 ops/ms
# Warmup Iteration   3: 5.902 ops/ms
Iteration   1: 5.680 ops/ms
Iteration   2: 6.509 ops/ms
Iteration   3: 6.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.225 ±(99.9%) 8.610 ops/ms [Average]
  (min, avg, max) = (5.680, 6.225, 6.509), stdev = 0.472
  CI (99.9%): [≈ 0, 14.835] (assumes normal distribution)


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
# Warmup Iteration   1: 16.882 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 5.419 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.438 ±(99.9%) 0.007 ms/op
Iteration   1: 4.241 ±(99.9%) 0.005 ms/op
Iteration   2: 4.294 ±(99.9%) 0.008 ms/op
Iteration   3: 4.274 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.270 ±(99.9%) 0.491 ms/op [Average]
  (min, avg, max) = (4.241, 4.270, 4.294), stdev = 0.027
  CI (99.9%): [3.778, 4.761] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.995 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.005 ms/op
Iteration   1: 4.261 ±(99.9%) 0.006 ms/op
Iteration   2: 4.198 ±(99.9%) 0.006 ms/op
Iteration   3: 4.509 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.322 ±(99.9%) 3.005 ms/op [Average]
  (min, avg, max) = (4.198, 4.322, 4.509), stdev = 0.165
  CI (99.9%): [1.318, 7.327] (assumes normal distribution)


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
# Warmup Iteration   1: 15.984 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.046 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.574 ±(99.9%) 0.009 ms/op
Iteration   1: 4.506 ±(99.9%) 0.007 ms/op
Iteration   2: 4.546 ±(99.9%) 0.006 ms/op
Iteration   3: 4.367 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.473 ±(99.9%) 1.711 ms/op [Average]
  (min, avg, max) = (4.367, 4.473, 4.546), stdev = 0.094
  CI (99.9%): [2.762, 6.184] (assumes normal distribution)


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
# Warmup Iteration   1: 17.343 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.639 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.473 ±(99.9%) 0.005 ms/op
Iteration   1: 5.280 ±(99.9%) 0.012 ms/op
Iteration   2: 5.100 ±(99.9%) 0.012 ms/op
Iteration   3: 5.117 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.166 ±(99.9%) 1.813 ms/op [Average]
  (min, avg, max) = (5.100, 5.166, 5.280), stdev = 0.099
  CI (99.9%): [3.353, 6.979] (assumes normal distribution)


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
# Warmup Iteration   1: 13.163 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.928 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 4.928 ±(99.9%) 0.025 ms/op
Iteration   1: 4.658 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   6.103 ms/op
                 createUser·p0.95:   7.438 ms/op
                 createUser·p0.99:   10.130 ms/op
                 createUser·p0.999:  17.269 ms/op
                 createUser·p0.9999: 28.574 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   2: 4.382 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.968 ms/op
                 createUser·p0.50:   4.088 ms/op
                 createUser·p0.90:   5.284 ms/op
                 createUser·p0.95:   6.201 ms/op
                 createUser·p0.99:   8.831 ms/op
                 createUser·p0.999:  29.032 ms/op
                 createUser·p0.9999: 31.012 ms/op
                 createUser·p1.00:   31.359 ms/op

Iteration   3: 4.608 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.191 ms/op
                 createUser·p0.50:   4.170 ms/op
                 createUser·p0.90:   6.201 ms/op
                 createUser·p0.95:   7.332 ms/op
                 createUser·p0.99:   10.371 ms/op
                 createUser·p0.999:  26.935 ms/op
                 createUser·p0.9999: 35.930 ms/op
                 createUser·p1.00:   38.273 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 211019
  mean =      4.546 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 267 
    [ 2.500,  5.000) = 172996 
    [ 5.000,  7.500) = 29749 
    [ 7.500, 10.000) = 5961 
    [10.000, 12.500) = 1234 
    [12.500, 15.000) = 337 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 89 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.722 ms/op
     p(50.0000) =      4.166 ms/op
     p(90.0000) =      5.800 ms/op
     p(95.0000) =      7.078 ms/op
     p(99.0000) =      9.929 ms/op
     p(99.9000) =     26.804 ms/op
     p(99.9900) =     34.006 ms/op
     p(99.9990) =     36.700 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


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
# Warmup Iteration   1: 14.506 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 4.914 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.572 ±(99.9%) 0.018 ms/op
Iteration   1: 4.487 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.009 ms/op
                 existUser·p0.50:   4.108 ms/op
                 existUser·p0.90:   5.743 ms/op
                 existUser·p0.95:   7.045 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  19.694 ms/op
                 existUser·p0.9999: 27.778 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   2: 4.343 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.410 ms/op
                 existUser·p0.50:   4.063 ms/op
                 existUser·p0.90:   5.333 ms/op
                 existUser·p0.95:   6.488 ms/op
                 existUser·p0.99:   9.535 ms/op
                 existUser·p0.999:  18.776 ms/op
                 existUser·p0.9999: 32.864 ms/op
                 existUser·p1.00:   34.603 ms/op

Iteration   3: 4.441 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.077 ms/op
                 existUser·p0.50:   4.035 ms/op
                 existUser·p0.90:   5.767 ms/op
                 existUser·p0.95:   7.037 ms/op
                 existUser·p0.99:   10.230 ms/op
                 existUser·p0.999:  18.965 ms/op
                 existUser·p0.9999: 31.837 ms/op
                 existUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 216967
  mean =      4.423 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 200 
    [ 2.500,  5.000) = 184980 
    [ 5.000,  7.500) = 24597 
    [ 7.500, 10.000) = 4953 
    [10.000, 12.500) = 1365 
    [12.500, 15.000) = 573 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 69 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.865 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     31.959 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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
# Warmup Iteration   1: 14.464 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.282 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.432 ±(99.9%) 0.018 ms/op
Iteration   1: 4.563 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.146 ms/op
                 getUser·p0.50:   4.190 ms/op
                 getUser·p0.90:   5.882 ms/op
                 getUser·p0.95:   7.070 ms/op
                 getUser·p0.99:   10.404 ms/op
                 getUser·p0.999:  18.772 ms/op
                 getUser·p0.9999: 29.718 ms/op
                 getUser·p1.00:   30.409 ms/op

Iteration   2: 4.424 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   4.121 ms/op
                 getUser·p0.90:   5.349 ms/op
                 getUser·p0.95:   6.562 ms/op
                 getUser·p0.99:   9.601 ms/op
                 getUser·p0.999:  18.383 ms/op
                 getUser·p0.9999: 33.121 ms/op
                 getUser·p1.00:   33.751 ms/op

Iteration   3: 4.269 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   4.071 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.530 ms/op
                 getUser·p0.99:   8.110 ms/op
                 getUser·p0.999:  31.032 ms/op
                 getUser·p0.9999: 35.816 ms/op
                 getUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 217447
  mean =      4.415 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 190198 
    [ 5.000,  7.500) = 21521 
    [ 7.500, 10.000) = 3926 
    [10.000, 12.500) = 1092 
    [12.500, 15.000) = 302 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 47 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      4.121 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      6.586 ms/op
     p(99.0000) =      9.470 ms/op
     p(99.9000) =     25.751 ms/op
     p(99.9900) =     34.833 ms/op
     p(99.9990) =     37.298 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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
# Warmup Iteration   1: 16.451 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 6.511 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.199 ±(99.9%) 0.020 ms/op
Iteration   1: 5.252 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.513 ms/op
                 listUser·p0.50:   4.817 ms/op
                 listUser·p0.90:   6.365 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   11.420 ms/op
                 listUser·p0.999:  25.923 ms/op
                 listUser·p0.9999: 31.910 ms/op
                 listUser·p1.00:   32.506 ms/op

Iteration   2: 5.237 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   4.899 ms/op
                 listUser·p0.90:   6.111 ms/op
                 listUser·p0.95:   7.578 ms/op
                 listUser·p0.99:   11.131 ms/op
                 listUser·p0.999:  25.873 ms/op
                 listUser·p0.9999: 33.694 ms/op
                 listUser·p1.00:   35.652 ms/op

Iteration   3: 4.723 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.579 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  17.647 ms/op
                 listUser·p0.9999: 21.332 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 189557
  mean =      5.059 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 130583 
    [ 5.000,  7.500) = 50374 
    [ 7.500, 10.000) = 6232 
    [10.000, 12.500) = 1470 
    [12.500, 15.000) = 402 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      7.250 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     23.902 ms/op
     p(99.9900) =     31.392 ms/op
     p(99.9990) =     35.006 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.763 ± 3.407  ops/ms
ClientPb.existUser                       thrpt       3   7.401 ± 4.511  ops/ms
ClientPb.getUser                         thrpt       3   7.029 ± 1.385  ops/ms
ClientPb.listUser                        thrpt       3   6.225 ± 8.610  ops/ms
ClientPb.createUser                       avgt       3   4.270 ± 0.491   ms/op
ClientPb.existUser                        avgt       3   4.322 ± 3.005   ms/op
ClientPb.getUser                          avgt       3   4.473 ± 1.711   ms/op
ClientPb.listUser                         avgt       3   5.166 ± 1.813   ms/op
ClientPb.createUser                     sample  211019   4.546 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.722           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.800           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.078           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.929           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.804           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.006           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.273           ms/op
ClientPb.existUser                      sample  216967   4.423 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.410           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.612           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.865           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.043           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.809           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.959           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.603           ms/op
ClientPb.getUser                        sample  217447   4.415 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.309           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.276           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.586           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.470           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.751           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.833           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.356           ms/op
ClientPb.listUser                       sample  189557   5.059 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.513           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.882           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.250           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.568           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.902           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.392           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.652           ms/op
