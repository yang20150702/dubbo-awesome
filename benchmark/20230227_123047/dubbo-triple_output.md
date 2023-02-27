# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.284 ops/ms
# Warmup Iteration   2: 6.173 ops/ms
# Warmup Iteration   3: 8.855 ops/ms
Iteration   1: 9.333 ops/ms
Iteration   2: 9.249 ops/ms
Iteration   3: 9.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.269 ±(99.9%) 1.027 ops/ms [Average]
  (min, avg, max) = (9.226, 9.269, 9.333), stdev = 0.056
  CI (99.9%): [8.243, 10.296] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.918 ops/ms
# Warmup Iteration   2: 8.692 ops/ms
# Warmup Iteration   3: 9.710 ops/ms
Iteration   1: 9.527 ops/ms
Iteration   2: 9.802 ops/ms
Iteration   3: 9.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.767 ±(99.9%) 4.110 ops/ms [Average]
  (min, avg, max) = (9.527, 9.767, 9.973), stdev = 0.225
  CI (99.9%): [5.657, 13.878] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.046 ops/ms
# Warmup Iteration   2: 8.562 ops/ms
# Warmup Iteration   3: 9.245 ops/ms
Iteration   1: 9.208 ops/ms
Iteration   2: 9.545 ops/ms
Iteration   3: 9.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.443 ±(99.9%) 3.732 ops/ms [Average]
  (min, avg, max) = (9.208, 9.443, 9.577), stdev = 0.205
  CI (99.9%): [5.712, 13.175] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.263 ops/ms
# Warmup Iteration   2: 7.526 ops/ms
# Warmup Iteration   3: 7.547 ops/ms
Iteration   1: 7.777 ops/ms
Iteration   2: 8.234 ops/ms
Iteration   3: 8.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.090 ±(99.9%) 4.952 ops/ms [Average]
  (min, avg, max) = (7.777, 8.090, 8.259), stdev = 0.271
  CI (99.9%): [3.138, 13.042] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.698 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.833 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.006 ms/op
Iteration   1: 3.394 ±(99.9%) 0.009 ms/op
Iteration   2: 3.452 ±(99.9%) 0.003 ms/op
Iteration   3: 3.324 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.390 ±(99.9%) 1.174 ms/op [Average]
  (min, avg, max) = (3.324, 3.390, 3.452), stdev = 0.064
  CI (99.9%): [2.216, 4.564] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.519 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.008 ms/op
Iteration   1: 3.308 ±(99.9%) 0.007 ms/op
Iteration   2: 3.245 ±(99.9%) 0.004 ms/op
Iteration   3: 3.288 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.280 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (3.245, 3.280, 3.308), stdev = 0.032
  CI (99.9%): [2.691, 3.870] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.622 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.006 ms/op
Iteration   1: 3.719 ±(99.9%) 0.005 ms/op
Iteration   2: 3.369 ±(99.9%) 0.011 ms/op
Iteration   3: 3.332 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.473 ±(99.9%) 3.900 ms/op [Average]
  (min, avg, max) = (3.332, 3.473, 3.719), stdev = 0.214
  CI (99.9%): [≈ 0, 7.373] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.446 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.006 ms/op
Iteration   1: 4.103 ±(99.9%) 0.006 ms/op
Iteration   2: 3.804 ±(99.9%) 0.014 ms/op
Iteration   3: 3.847 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.918 ±(99.9%) 2.951 ms/op [Average]
  (min, avg, max) = (3.804, 3.918, 4.103), stdev = 0.162
  CI (99.9%): [0.967, 6.869] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.187 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.010 ms/op
Iteration   1: 3.410 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  19.366 ms/op
                 createUser·p0.9999: 24.400 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   2: 3.431 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  20.959 ms/op
                 createUser·p0.9999: 24.641 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 3.493 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.694 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  19.464 ms/op
                 createUser·p0.9999: 27.914 ms/op
                 createUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278522
  mean =      3.444 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8043 
    [ 2.500,  5.000) = 261976 
    [ 5.000,  7.500) = 7422 
    [ 7.500, 10.000) = 591 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     28.703 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.887 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.009 ms/op
Iteration   1: 3.261 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  9.896 ms/op
                 existUser·p0.9999: 22.563 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   2: 3.379 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  21.090 ms/op
                 existUser·p0.9999: 23.724 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   3: 3.298 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.343 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  18.973 ms/op
                 existUser·p0.9999: 26.509 ms/op
                 existUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289751
  mean =      3.312 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10349 
    [ 2.500,  5.000) = 274139 
    [ 5.000,  7.500) = 4351 
    [ 7.500, 10.000) = 449 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.714 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     24.419 ms/op
     p(99.9990) =     26.611 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.161 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.007 ms/op
Iteration   1: 3.474 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.799 ms/op
                 getUser·p0.999:  17.721 ms/op
                 getUser·p0.9999: 19.850 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   2: 3.445 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.548 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  19.497 ms/op
                 getUser·p0.9999: 22.634 ms/op
                 getUser·p1.00:   23.658 ms/op

Iteration   3: 3.455 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.817 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  16.739 ms/op
                 getUser·p0.9999: 27.484 ms/op
                 getUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277598
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2752 
    [ 2.500,  5.000) = 265508 
    [ 5.000,  7.500) = 7997 
    [ 7.500, 10.000) = 746 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 166 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     18.101 ms/op
     p(99.9900) =     26.771 ms/op
     p(99.9990) =     30.613 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.232 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.012 ms/op
Iteration   1: 3.946 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  17.456 ms/op
                 listUser·p0.9999: 23.802 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   2: 4.117 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  14.739 ms/op
                 listUser·p0.9999: 24.969 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   3: 4.072 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.609 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 18.668 ms/op
                 listUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237192
  mean =      4.044 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 226749 
    [ 5.000,  7.500) = 8372 
    [ 7.500, 10.000) = 1181 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 304 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.667 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     16.020 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.269 ± 1.027  ops/ms
ClientPb.existUser                       thrpt       3   9.767 ± 4.110  ops/ms
ClientPb.getUser                         thrpt       3   9.443 ± 3.732  ops/ms
ClientPb.listUser                        thrpt       3   8.090 ± 4.952  ops/ms
ClientPb.createUser                       avgt       3   3.390 ± 1.174   ms/op
ClientPb.existUser                        avgt       3   3.280 ± 0.590   ms/op
ClientPb.getUser                          avgt       3   3.473 ± 3.900   ms/op
ClientPb.listUser                         avgt       3   3.918 ± 2.951   ms/op
ClientPb.createUser                     sample  278522   3.444 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.137           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.218           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.464           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.197           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.262           ms/op
ClientPb.existUser                      sample  289751   3.312 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.343           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.022           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.714           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.973           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.419           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.739           ms/op
ClientPb.getUser                        sample  277598   3.458 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.331           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.702           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.636           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.101           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.771           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.867           ms/op
ClientPb.listUser                       sample  237192   4.044 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.667           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.907           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.193           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.020           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.757           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.035           ms/op
