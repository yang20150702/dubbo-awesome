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
# Warmup Iteration   1: 1.948 ops/ms
# Warmup Iteration   2: 4.925 ops/ms
# Warmup Iteration   3: 8.733 ops/ms
Iteration   1: 9.288 ops/ms
Iteration   2: 9.248 ops/ms
Iteration   3: 9.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.241 ±(99.9%) 0.932 ops/ms [Average]
  (min, avg, max) = (9.186, 9.241, 9.288), stdev = 0.051
  CI (99.9%): [8.309, 10.173] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.892 ops/ms
# Warmup Iteration   2: 8.806 ops/ms
# Warmup Iteration   3: 9.545 ops/ms
Iteration   1: 9.733 ops/ms
Iteration   2: 9.965 ops/ms
Iteration   3: 9.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.783 ±(99.9%) 2.958 ops/ms [Average]
  (min, avg, max) = (9.652, 9.783, 9.965), stdev = 0.162
  CI (99.9%): [6.825, 12.742] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.978 ops/ms
# Warmup Iteration   2: 8.241 ops/ms
# Warmup Iteration   3: 9.025 ops/ms
Iteration   1: 9.160 ops/ms
Iteration   2: 9.211 ops/ms
Iteration   3: 9.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.149 ±(99.9%) 1.248 ops/ms [Average]
  (min, avg, max) = (9.075, 9.149, 9.211), stdev = 0.068
  CI (99.9%): [7.901, 10.397] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.855 ops/ms
# Warmup Iteration   2: 7.102 ops/ms
# Warmup Iteration   3: 7.787 ops/ms
Iteration   1: 7.783 ops/ms
Iteration   2: 7.814 ops/ms
Iteration   3: 7.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.853 ±(99.9%) 1.731 ops/ms [Average]
  (min, avg, max) = (7.783, 7.853, 7.961), stdev = 0.095
  CI (99.9%): [6.122, 9.583] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.970 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.002 ms/op
Iteration   1: 3.398 ±(99.9%) 0.004 ms/op
Iteration   2: 3.394 ±(99.9%) 0.006 ms/op
Iteration   3: 3.453 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.415 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (3.394, 3.415, 3.453), stdev = 0.033
  CI (99.9%): [2.816, 4.014] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.846 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.513 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.004 ms/op
Iteration   1: 3.332 ±(99.9%) 0.006 ms/op
Iteration   2: 3.313 ±(99.9%) 0.003 ms/op
Iteration   3: 3.267 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.304 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.267, 3.304, 3.332), stdev = 0.034
  CI (99.9%): [2.687, 3.921] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.850 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.004 ms/op
Iteration   1: 3.479 ±(99.9%) 0.005 ms/op
Iteration   2: 3.412 ±(99.9%) 0.004 ms/op
Iteration   3: 3.427 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.440 ±(99.9%) 0.639 ms/op [Average]
  (min, avg, max) = (3.412, 3.440, 3.479), stdev = 0.035
  CI (99.9%): [2.801, 4.078] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.864 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.177 ±(99.9%) 0.003 ms/op
Iteration   1: 4.184 ±(99.9%) 0.005 ms/op
Iteration   2: 4.090 ±(99.9%) 0.007 ms/op
Iteration   3: 3.970 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.081 ±(99.9%) 1.959 ms/op [Average]
  (min, avg, max) = (3.970, 4.081, 4.184), stdev = 0.107
  CI (99.9%): [2.122, 6.041] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.488 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.008 ms/op
Iteration   1: 3.454 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  20.037 ms/op
                 createUser·p0.9999: 23.224 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   2: 3.461 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.559 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.071 ms/op
                 createUser·p0.999:  22.788 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   3: 3.423 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  19.514 ms/op
                 createUser·p0.9999: 23.667 ms/op
                 createUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278391
  mean =      3.446 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6013 
    [ 2.500,  5.000) = 267508 
    [ 5.000,  7.500) = 3860 
    [ 7.500, 10.000) = 401 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     19.779 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.227 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.009 ms/op
Iteration   1: 3.388 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  19.386 ms/op
                 existUser·p0.9999: 22.075 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   2: 3.492 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   7.086 ms/op
                 existUser·p0.999:  21.856 ms/op
                 existUser·p0.9999: 24.768 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   3: 3.325 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   5.798 ms/op
                 existUser·p0.999:  19.198 ms/op
                 existUser·p0.9999: 26.162 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282098
  mean =      3.400 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8174 
    [ 2.500,  5.000) = 268396 
    [ 5.000,  7.500) = 4308 
    [ 7.500, 10.000) = 507 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     19.330 ms/op
     p(99.9900) =     24.766 ms/op
     p(99.9990) =     26.649 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.808 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.012 ms/op
Iteration   1: 3.557 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   7.660 ms/op
                 getUser·p0.999:  20.972 ms/op
                 getUser·p0.9999: 23.068 ms/op
                 getUser·p1.00:   31.195 ms/op

Iteration   2: 3.408 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   5.516 ms/op
                 getUser·p0.999:  7.479 ms/op
                 getUser·p0.9999: 24.157 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   3: 3.492 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  18.365 ms/op
                 getUser·p0.9999: 27.041 ms/op
                 getUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275551
  mean =      3.485 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4101 
    [ 2.500,  5.000) = 264046 
    [ 5.000,  7.500) = 5820 
    [ 7.500, 10.000) = 975 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     29.909 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.147 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.577 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.012 ms/op
Iteration   1: 4.201 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.765 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  21.782 ms/op
                 listUser·p0.9999: 24.691 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   2: 4.134 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  16.138 ms/op
                 listUser·p0.9999: 18.203 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 4.118 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  14.615 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231469
  mean =      4.151 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 223469 
    [ 5.000,  7.500) = 6070 
    [ 7.500, 10.000) = 979 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.765 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.146 ms/op
     p(99.9000) =     16.845 ms/op
     p(99.9900) =     23.818 ms/op
     p(99.9990) =     25.551 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.241 ± 0.932  ops/ms
ClientPb.existUser                       thrpt       3   9.783 ± 2.958  ops/ms
ClientPb.getUser                         thrpt       3   9.149 ± 1.248  ops/ms
ClientPb.listUser                        thrpt       3   7.853 ± 1.731  ops/ms
ClientPb.createUser                       avgt       3   3.415 ± 0.599   ms/op
ClientPb.existUser                        avgt       3   3.304 ± 0.617   ms/op
ClientPb.getUser                          avgt       3   3.440 ± 0.639   ms/op
ClientPb.listUser                         avgt       3   4.081 ± 1.959   ms/op
ClientPb.createUser                     sample  278391   3.446 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.366           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.825           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.779           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.936           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.821           ms/op
ClientPb.existUser                      sample  282098   3.400 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.528           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.100           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.136           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.330           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.766           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.903           ms/op
ClientPb.getUser                        sample  275551   3.485 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.333           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.906           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.366           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.297           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.195           ms/op
ClientPb.listUser                       sample  231469   4.151 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.765           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.146           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.845           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.818           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.034           ms/op
