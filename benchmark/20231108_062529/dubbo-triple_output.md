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
# Warmup Iteration   1: 1.116 ops/ms
# Warmup Iteration   2: 2.380 ops/ms
# Warmup Iteration   3: 5.361 ops/ms
Iteration   1: 5.643 ops/ms
Iteration   2: 5.948 ops/ms
Iteration   3: 6.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.875 ±(99.9%) 3.756 ops/ms [Average]
  (min, avg, max) = (5.643, 5.875, 6.035), stdev = 0.206
  CI (99.9%): [2.119, 9.632] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.700 ops/ms
# Warmup Iteration   2: 4.708 ops/ms
# Warmup Iteration   3: 5.947 ops/ms
Iteration   1: 6.217 ops/ms
Iteration   2: 6.215 ops/ms
Iteration   3: 6.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.186 ±(99.9%) 0.951 ops/ms [Average]
  (min, avg, max) = (6.125, 6.186, 6.217), stdev = 0.052
  CI (99.9%): [5.235, 7.137] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.547 ops/ms
# Warmup Iteration   2: 4.458 ops/ms
# Warmup Iteration   3: 5.915 ops/ms
Iteration   1: 5.862 ops/ms
Iteration   2: 5.877 ops/ms
Iteration   3: 5.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.888 ±(99.9%) 0.604 ops/ms [Average]
  (min, avg, max) = (5.862, 5.888, 5.926), stdev = 0.033
  CI (99.9%): [5.285, 6.492] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.684 ops/ms
# Warmup Iteration   2: 4.200 ops/ms
# Warmup Iteration   3: 5.325 ops/ms
Iteration   1: 5.392 ops/ms
Iteration   2: 5.217 ops/ms
Iteration   3: 5.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.326 ±(99.9%) 1.736 ops/ms [Average]
  (min, avg, max) = (5.217, 5.326, 5.392), stdev = 0.095
  CI (99.9%): [3.590, 7.062] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 17.364 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 6.569 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.870 ±(99.9%) 0.009 ms/op
Iteration   1: 5.453 ±(99.9%) 0.007 ms/op
Iteration   2: 5.396 ±(99.9%) 0.014 ms/op
Iteration   3: 5.301 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.383 ±(99.9%) 1.398 ms/op [Average]
  (min, avg, max) = (5.301, 5.383, 5.453), stdev = 0.077
  CI (99.9%): [3.985, 6.782] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 16.088 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 6.171 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.258 ±(99.9%) 0.006 ms/op
Iteration   1: 5.146 ±(99.9%) 0.007 ms/op
Iteration   2: 5.084 ±(99.9%) 0.007 ms/op
Iteration   3: 4.995 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.075 ±(99.9%) 1.386 ms/op [Average]
  (min, avg, max) = (4.995, 5.075, 5.146), stdev = 0.076
  CI (99.9%): [3.689, 6.461] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 19.770 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 7.122 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.773 ±(99.9%) 0.013 ms/op
Iteration   1: 5.596 ±(99.9%) 0.008 ms/op
Iteration   2: 5.338 ±(99.9%) 0.011 ms/op
Iteration   3: 5.331 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.422 ±(99.9%) 2.750 ms/op [Average]
  (min, avg, max) = (5.331, 5.422, 5.596), stdev = 0.151
  CI (99.9%): [2.672, 8.172] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 20.046 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 7.720 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.471 ±(99.9%) 0.007 ms/op
Iteration   1: 6.237 ±(99.9%) 0.010 ms/op
Iteration   2: 6.085 ±(99.9%) 0.015 ms/op
Iteration   3: 6.053 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.125 ±(99.9%) 1.799 ms/op [Average]
  (min, avg, max) = (6.053, 6.125, 6.237), stdev = 0.099
  CI (99.9%): [4.326, 7.924] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 16.668 ±(99.9%) 0.257 ms/op
# Warmup Iteration   2: 6.525 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.716 ±(99.9%) 0.024 ms/op
Iteration   1: 5.424 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   5.128 ms/op
                 createUser·p0.90:   6.726 ms/op
                 createUser·p0.95:   7.660 ms/op
                 createUser·p0.99:   10.091 ms/op
                 createUser·p0.999:  22.118 ms/op
                 createUser·p0.9999: 27.168 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   2: 5.524 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.870 ms/op
                 createUser·p0.50:   5.177 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   7.848 ms/op
                 createUser·p0.99:   10.911 ms/op
                 createUser·p0.999:  24.284 ms/op
                 createUser·p0.9999: 28.025 ms/op
                 createUser·p1.00:   29.491 ms/op

Iteration   3: 5.371 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.245 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.406 ms/op
                 createUser·p0.95:   6.988 ms/op
                 createUser·p0.99:   9.732 ms/op
                 createUser·p0.999:  27.046 ms/op
                 createUser·p0.9999: 31.557 ms/op
                 createUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176450
  mean =      5.439 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 74498 
    [ 5.000,  7.500) = 92583 
    [ 7.500, 10.000) = 7362 
    [10.000, 12.500) = 1206 
    [12.500, 15.000) = 384 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.709 ms/op
     p(95.0000) =      7.569 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     23.599 ms/op
     p(99.9900) =     30.284 ms/op
     p(99.9990) =     31.716 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 15.320 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 5.865 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.346 ±(99.9%) 0.020 ms/op
Iteration   1: 5.402 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.761 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   7.274 ms/op
                 existUser·p0.95:   8.364 ms/op
                 existUser·p0.99:   11.125 ms/op
                 existUser·p0.999:  23.063 ms/op
                 existUser·p0.9999: 26.597 ms/op
                 existUser·p1.00:   29.262 ms/op

Iteration   2: 5.391 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.454 ms/op
                 existUser·p0.50:   5.038 ms/op
                 existUser·p0.90:   6.808 ms/op
                 existUser·p0.95:   7.635 ms/op
                 existUser·p0.99:   10.648 ms/op
                 existUser·p0.999:  24.707 ms/op
                 existUser·p0.9999: 29.496 ms/op
                 existUser·p1.00:   30.278 ms/op

Iteration   3: 5.274 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.913 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.562 ms/op
                 existUser·p0.95:   7.504 ms/op
                 existUser·p0.99:   10.174 ms/op
                 existUser·p0.999:  15.751 ms/op
                 existUser·p0.9999: 32.014 ms/op
                 existUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179110
  mean =      5.355 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 92372 
    [ 5.000,  7.500) = 75168 
    [ 7.500, 10.000) = 9158 
    [10.000, 12.500) = 1622 
    [12.500, 15.000) = 476 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.761 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      7.889 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     21.660 ms/op
     p(99.9900) =     30.123 ms/op
     p(99.9990) =     32.667 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.034 ±(99.9%) 0.241 ms/op
# Warmup Iteration   2: 6.724 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.697 ±(99.9%) 0.024 ms/op
Iteration   1: 5.836 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.122 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   8.110 ms/op
                 getUser·p0.95:   9.667 ms/op
                 getUser·p0.99:   13.681 ms/op
                 getUser·p0.999:  21.240 ms/op
                 getUser·p0.9999: 28.676 ms/op
                 getUser·p1.00:   29.721 ms/op

Iteration   2: 5.787 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   7.774 ms/op
                 getUser·p0.95:   9.208 ms/op
                 getUser·p0.99:   13.851 ms/op
                 getUser·p0.999:  28.647 ms/op
                 getUser·p0.9999: 47.807 ms/op
                 getUser·p1.00:   48.824 ms/op

Iteration   3: 5.395 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   6.955 ms/op
                 getUser·p0.95:   8.077 ms/op
                 getUser·p0.99:   11.223 ms/op
                 getUser·p0.999:  29.491 ms/op
                 getUser·p0.9999: 31.911 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169394
  mean =      5.665 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 72539 
    [ 5.000, 10.000) = 91290 
    [10.000, 15.000) = 4826 
    [15.000, 20.000) = 503 
    [20.000, 25.000) = 66 
    [25.000, 30.000) = 79 
    [30.000, 35.000) = 59 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      7.561 ms/op
     p(95.0000) =      9.060 ms/op
     p(99.0000) =     12.993 ms/op
     p(99.9000) =     25.396 ms/op
     p(99.9900) =     42.926 ms/op
     p(99.9990) =     48.279 ms/op
     p(99.9999) =     48.824 ms/op
    p(100.0000) =     48.824 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.105 ±(99.9%) 0.317 ms/op
# Warmup Iteration   2: 7.598 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 6.050 ±(99.9%) 0.027 ms/op
Iteration   1: 5.984 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   5.603 ms/op
                 listUser·p0.90:   7.119 ms/op
                 listUser·p0.95:   8.716 ms/op
                 listUser·p0.99:   12.337 ms/op
                 listUser·p0.999:  25.752 ms/op
                 listUser·p0.9999: 31.412 ms/op
                 listUser·p1.00:   32.342 ms/op

Iteration   2: 5.814 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   8.176 ms/op
                 listUser·p0.99:   12.173 ms/op
                 listUser·p0.999:  27.362 ms/op
                 listUser·p0.9999: 30.540 ms/op
                 listUser·p1.00:   34.013 ms/op

Iteration   3: 6.140 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.548 ms/op
                 listUser·p0.50:   5.800 ms/op
                 listUser·p0.90:   7.209 ms/op
                 listUser·p0.95:   8.995 ms/op
                 listUser·p0.99:   12.698 ms/op
                 listUser·p0.999:  22.377 ms/op
                 listUser·p0.9999: 28.789 ms/op
                 listUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 160555
  mean =      5.976 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 19552 
    [ 5.000,  7.500) = 128216 
    [ 7.500, 10.000) = 8716 
    [10.000, 12.500) = 2516 
    [12.500, 15.000) = 926 
    [15.000, 17.500) = 206 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.335 ms/op
     p(50.0000) =      5.612 ms/op
     p(90.0000) =      7.086 ms/op
     p(95.0000) =      8.684 ms/op
     p(99.0000) =     12.435 ms/op
     p(99.9000) =     25.967 ms/op
     p(99.9900) =     30.605 ms/op
     p(99.9990) =     33.001 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.875 ± 3.756  ops/ms
ClientPb.existUser                       thrpt       3   6.186 ± 0.951  ops/ms
ClientPb.getUser                         thrpt       3   5.888 ± 0.604  ops/ms
ClientPb.listUser                        thrpt       3   5.326 ± 1.736  ops/ms
ClientPb.createUser                       avgt       3   5.383 ± 1.398   ms/op
ClientPb.existUser                        avgt       3   5.075 ± 1.386   ms/op
ClientPb.getUser                          avgt       3   5.422 ± 2.750   ms/op
ClientPb.listUser                         avgt       3   6.125 ± 1.799   ms/op
ClientPb.createUser                     sample  176450   5.439 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.761           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.153           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.709           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.569           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.207           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.599           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.284           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.916           ms/op
ClientPb.existUser                      sample  179110   5.355 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.761           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.973           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.857           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.889           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.682           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.660           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.123           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.030           ms/op
ClientPb.getUser                        sample  169394   5.665 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.846           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.153           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.561           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.060           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.993           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.396           ms/op
ClientPb.getUser:getUser·p0.9999        sample          42.926           ms/op
ClientPb.getUser:getUser·p1.00          sample          48.824           ms/op
ClientPb.listUser                       sample  160555   5.976 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.335           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.086           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.684           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.435           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.967           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.605           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.013           ms/op
