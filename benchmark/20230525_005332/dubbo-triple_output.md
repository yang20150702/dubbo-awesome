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
# Warmup Iteration   1: 2.106 ops/ms
# Warmup Iteration   2: 5.551 ops/ms
# Warmup Iteration   3: 8.856 ops/ms
Iteration   1: 9.474 ops/ms
Iteration   2: 9.487 ops/ms
Iteration   3: 9.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.439 ±(99.9%) 1.329 ops/ms [Average]
  (min, avg, max) = (9.355, 9.439, 9.487), stdev = 0.073
  CI (99.9%): [8.110, 10.768] (assumes normal distribution)


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
# Warmup Iteration   1: 2.705 ops/ms
# Warmup Iteration   2: 8.232 ops/ms
# Warmup Iteration   3: 9.055 ops/ms
Iteration   1: 9.660 ops/ms
Iteration   2: 10.046 ops/ms
Iteration   3: 9.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.833 ±(99.9%) 3.572 ops/ms [Average]
  (min, avg, max) = (9.660, 9.833, 10.046), stdev = 0.196
  CI (99.9%): [6.262, 13.405] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.093 ops/ms
# Warmup Iteration   2: 8.678 ops/ms
# Warmup Iteration   3: 9.162 ops/ms
Iteration   1: 8.943 ops/ms
Iteration   2: 9.681 ops/ms
Iteration   3: 9.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.397 ±(99.9%) 7.245 ops/ms [Average]
  (min, avg, max) = (8.943, 9.397, 9.681), stdev = 0.397
  CI (99.9%): [2.151, 16.642] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.660 ops/ms
# Warmup Iteration   2: 7.083 ops/ms
# Warmup Iteration   3: 7.957 ops/ms
Iteration   1: 7.829 ops/ms
Iteration   2: 8.017 ops/ms
Iteration   3: 8.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.051 ±(99.9%) 4.403 ops/ms [Average]
  (min, avg, max) = (7.829, 8.051, 8.308), stdev = 0.241
  CI (99.9%): [3.648, 12.454] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.971 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.008 ms/op
Iteration   1: 3.408 ±(99.9%) 0.007 ms/op
Iteration   2: 3.492 ±(99.9%) 0.007 ms/op
Iteration   3: 3.400 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.433 ±(99.9%) 0.929 ms/op [Average]
  (min, avg, max) = (3.400, 3.433, 3.492), stdev = 0.051
  CI (99.9%): [2.505, 4.362] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.747 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.005 ms/op
Iteration   1: 3.348 ±(99.9%) 0.002 ms/op
Iteration   2: 3.284 ±(99.9%) 0.007 ms/op
Iteration   3: 3.421 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.351 ±(99.9%) 1.246 ms/op [Average]
  (min, avg, max) = (3.284, 3.351, 3.421), stdev = 0.068
  CI (99.9%): [2.105, 4.597] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.710 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.005 ms/op
Iteration   1: 3.451 ±(99.9%) 0.009 ms/op
Iteration   2: 3.436 ±(99.9%) 0.008 ms/op
Iteration   3: 3.703 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.530 ±(99.9%) 2.732 ms/op [Average]
  (min, avg, max) = (3.436, 3.530, 3.703), stdev = 0.150
  CI (99.9%): [0.798, 6.262] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.623 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.306 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.011 ms/op
Iteration   1: 3.976 ±(99.9%) 0.009 ms/op
Iteration   2: 3.880 ±(99.9%) 0.013 ms/op
Iteration   3: 3.847 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.901 ±(99.9%) 1.224 ms/op [Average]
  (min, avg, max) = (3.847, 3.901, 3.976), stdev = 0.067
  CI (99.9%): [2.677, 5.125] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.181 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.010 ms/op
Iteration   1: 3.573 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   5.661 ms/op
                 createUser·p0.99:   7.366 ms/op
                 createUser·p0.999:  18.874 ms/op
                 createUser·p0.9999: 34.738 ms/op
                 createUser·p1.00:   37.945 ms/op

Iteration   2: 3.482 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  20.808 ms/op
                 createUser·p0.9999: 24.084 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.420 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  18.919 ms/op
                 createUser·p0.9999: 26.252 ms/op
                 createUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275953
  mean =      3.478 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11102 
    [ 2.500,  5.000) = 254859 
    [ 5.000,  7.500) = 8492 
    [ 7.500, 10.000) = 1031 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     18.909 ms/op
     p(99.9900) =     34.119 ms/op
     p(99.9990) =     35.668 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.589 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.009 ms/op
Iteration   1: 3.311 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.468 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  14.924 ms/op
                 existUser·p0.9999: 22.490 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   2: 3.266 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  13.255 ms/op
                 existUser·p0.9999: 23.888 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   3: 3.346 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  17.380 ms/op
                 existUser·p0.9999: 25.082 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290196
  mean =      3.307 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3019 
    [ 2.500,  5.000) = 283011 
    [ 5.000,  7.500) = 3354 
    [ 7.500, 10.000) = 400 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     15.103 ms/op
     p(99.9900) =     24.215 ms/op
     p(99.9990) =     25.627 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 8.266 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.624 ±(99.9%) 0.011 ms/op
Iteration   1: 3.514 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.591 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.975 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  20.304 ms/op
                 getUser·p0.9999: 23.348 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   2: 3.407 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  21.755 ms/op
                 getUser·p0.9999: 25.652 ms/op
                 getUser·p1.00:   26.247 ms/op

Iteration   3: 3.493 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  17.658 ms/op
                 getUser·p0.9999: 27.784 ms/op
                 getUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276597
  mean =      3.471 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5279 
    [ 2.500,  5.000) = 262762 
    [ 5.000,  7.500) = 7138 
    [ 7.500, 10.000) = 902 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     26.783 ms/op
     p(99.9990) =     27.951 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 11.644 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.013 ms/op
Iteration   1: 3.984 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.921 ms/op
                 listUser·p0.999:  20.021 ms/op
                 listUser·p0.9999: 22.479 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   2: 3.939 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  15.254 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 3.908 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  13.697 ms/op
                 listUser·p0.9999: 15.637 ms/op
                 listUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243151
  mean =      3.943 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 235298 
    [ 5.000,  7.500) = 5499 
    [ 7.500, 10.000) = 1391 
    [10.000, 12.500) = 415 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.195 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     23.073 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.439 ± 1.329  ops/ms
ClientPb.existUser                       thrpt       3   9.833 ± 3.572  ops/ms
ClientPb.getUser                         thrpt       3   9.397 ± 7.245  ops/ms
ClientPb.listUser                        thrpt       3   8.051 ± 4.403  ops/ms
ClientPb.createUser                       avgt       3   3.433 ± 0.929   ms/op
ClientPb.existUser                        avgt       3   3.351 ± 1.246   ms/op
ClientPb.getUser                          avgt       3   3.530 ± 2.732   ms/op
ClientPb.listUser                         avgt       3   3.901 ± 1.224   ms/op
ClientPb.createUser                     sample  275953   3.478 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.420           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.391           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.971           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.909           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.119           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.945           ms/op
ClientPb.existUser                      sample  290196   3.307 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.417           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.103           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.215           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.673           ms/op
ClientPb.getUser                        sample  276597   3.471 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.591           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.881           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.783           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.344           ms/op
ClientPb.listUser                       sample  243151   3.943 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.195           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.254           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.561           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.233           ms/op
