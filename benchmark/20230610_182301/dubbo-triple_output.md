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
# Warmup Iteration   1: 2.281 ops/ms
# Warmup Iteration   2: 5.751 ops/ms
# Warmup Iteration   3: 8.868 ops/ms
Iteration   1: 9.576 ops/ms
Iteration   2: 9.796 ops/ms
Iteration   3: 9.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.685 ±(99.9%) 2.002 ops/ms [Average]
  (min, avg, max) = (9.576, 9.685, 9.796), stdev = 0.110
  CI (99.9%): [7.683, 11.687] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.468 ops/ms
# Warmup Iteration   2: 8.907 ops/ms
# Warmup Iteration   3: 10.086 ops/ms
Iteration   1: 10.554 ops/ms
Iteration   2: 10.594 ops/ms
Iteration   3: 10.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.523 ±(99.9%) 1.646 ops/ms [Average]
  (min, avg, max) = (10.421, 10.523, 10.594), stdev = 0.090
  CI (99.9%): [8.877, 12.169] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.128 ops/ms
# Warmup Iteration   2: 8.012 ops/ms
# Warmup Iteration   3: 9.370 ops/ms
Iteration   1: 9.641 ops/ms
Iteration   2: 9.851 ops/ms
Iteration   3: 10.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.868 ±(99.9%) 4.322 ops/ms [Average]
  (min, avg, max) = (9.641, 9.868, 10.113), stdev = 0.237
  CI (99.9%): [5.546, 14.190] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.439 ops/ms
# Warmup Iteration   2: 7.439 ops/ms
# Warmup Iteration   3: 8.301 ops/ms
Iteration   1: 8.509 ops/ms
Iteration   2: 8.433 ops/ms
Iteration   3: 8.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.546 ±(99.9%) 2.456 ops/ms [Average]
  (min, avg, max) = (8.433, 8.546, 8.695), stdev = 0.135
  CI (99.9%): [6.090, 11.002] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.736 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.007 ms/op
Iteration   1: 3.167 ±(99.9%) 0.006 ms/op
Iteration   2: 3.159 ±(99.9%) 0.010 ms/op
Iteration   3: 3.377 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.234 ±(99.9%) 2.248 ms/op [Average]
  (min, avg, max) = (3.159, 3.234, 3.377), stdev = 0.123
  CI (99.9%): [0.986, 5.483] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.085 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.004 ms/op
Iteration   1: 3.079 ±(99.9%) 0.004 ms/op
Iteration   2: 3.061 ±(99.9%) 0.003 ms/op
Iteration   3: 3.064 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.068 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (3.061, 3.068, 3.079), stdev = 0.010
  CI (99.9%): [2.888, 3.248] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.073 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.003 ms/op
Iteration   1: 3.207 ±(99.9%) 0.002 ms/op
Iteration   2: 3.115 ±(99.9%) 0.002 ms/op
Iteration   3: 3.163 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.162 ±(99.9%) 0.845 ms/op [Average]
  (min, avg, max) = (3.115, 3.162, 3.207), stdev = 0.046
  CI (99.9%): [2.317, 4.007] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.853 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.005 ms/op
Iteration   1: 3.936 ±(99.9%) 0.007 ms/op
Iteration   2: 3.942 ±(99.9%) 0.010 ms/op
Iteration   3: 4.157 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.012 ±(99.9%) 2.303 ms/op [Average]
  (min, avg, max) = (3.936, 4.012, 4.157), stdev = 0.126
  CI (99.9%): [1.709, 6.315] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.497 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.011 ms/op
Iteration   1: 3.500 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  16.318 ms/op
                 createUser·p0.9999: 19.005 ms/op
                 createUser·p1.00:   19.300 ms/op

Iteration   2: 3.366 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  16.597 ms/op
                 createUser·p0.9999: 19.202 ms/op
                 createUser·p1.00:   19.923 ms/op

Iteration   3: 3.371 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  17.072 ms/op
                 createUser·p0.9999: 23.413 ms/op
                 createUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281461
  mean =      3.411 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10911 
    [ 2.500,  5.000) = 261657 
    [ 5.000,  7.500) = 8054 
    [ 7.500, 10.000) = 400 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 156 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.901 ms/op
     p(99.9000) =     16.352 ms/op
     p(99.9900) =     21.631 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.697 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.009 ms/op
Iteration   1: 3.166 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  11.060 ms/op
                 existUser·p0.9999: 22.541 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  8.749 ms/op
                 existUser·p0.9999: 22.891 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   3: 3.150 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  9.388 ms/op
                 existUser·p0.9999: 23.907 ms/op
                 existUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305222
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16318 
    [ 2.500,  5.000) = 284465 
    [ 5.000,  7.500) = 3745 
    [ 7.500, 10.000) = 381 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     10.875 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     24.247 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 8.400 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.009 ms/op
Iteration   1: 3.266 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.427 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  13.872 ms/op
                 getUser·p0.9999: 20.959 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   2: 3.119 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  8.397 ms/op
                 getUser·p0.9999: 32.064 ms/op
                 getUser·p1.00:   32.473 ms/op

Iteration   3: 3.238 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   4.251 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  10.310 ms/op
                 getUser·p0.9999: 19.665 ms/op
                 getUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299093
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6054 
    [ 2.500,  5.000) = 284064 
    [ 5.000,  7.500) = 8040 
    [ 7.500, 10.000) = 572 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     11.402 ms/op
     p(99.9900) =     30.510 ms/op
     p(99.9990) =     32.440 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


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
# Warmup Iteration   1: 8.802 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.009 ms/op
Iteration   1: 3.868 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  13.850 ms/op
                 listUser·p0.9999: 19.718 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   2: 3.713 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.162 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  15.776 ms/op
                 listUser·p0.9999: 20.001 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.769 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  13.222 ms/op
                 listUser·p0.9999: 14.918 ms/op
                 listUser·p1.00:   15.466 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253652
  mean =      3.782 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 245264 
    [ 5.000,  7.500) = 6355 
    [ 7.500, 10.000) = 1371 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 211 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     20.087 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.685 ± 2.002  ops/ms
ClientPb.existUser                       thrpt       3  10.523 ± 1.646  ops/ms
ClientPb.getUser                         thrpt       3   9.868 ± 4.322  ops/ms
ClientPb.listUser                        thrpt       3   8.546 ± 2.456  ops/ms
ClientPb.createUser                       avgt       3   3.234 ± 2.248   ms/op
ClientPb.existUser                        avgt       3   3.068 ± 0.180   ms/op
ClientPb.getUser                          avgt       3   3.162 ± 0.845   ms/op
ClientPb.listUser                         avgt       3   4.012 ± 2.303   ms/op
ClientPb.createUser                     sample  281461   3.411 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.694           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.153           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.901           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.352           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.631           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.052           ms/op
ClientPb.existUser                      sample  305222   3.143 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.071           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.428           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.325           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.875           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.101           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.609           ms/op
ClientPb.getUser                        sample  299093   3.206 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.708           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.486           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.402           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.510           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.473           ms/op
ClientPb.listUser                       sample  253652   3.782 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.497           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.029           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.844           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.628           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.185           ms/op
