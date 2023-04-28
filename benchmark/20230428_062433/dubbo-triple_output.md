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
# Warmup Iteration   1: 2.068 ops/ms
# Warmup Iteration   2: 5.049 ops/ms
# Warmup Iteration   3: 8.323 ops/ms
Iteration   1: 8.970 ops/ms
Iteration   2: 8.903 ops/ms
Iteration   3: 9.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.007 ±(99.9%) 2.306 ops/ms [Average]
  (min, avg, max) = (8.903, 9.007, 9.147), stdev = 0.126
  CI (99.9%): [6.701, 11.312] (assumes normal distribution)


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
# Warmup Iteration   1: 2.519 ops/ms
# Warmup Iteration   2: 7.568 ops/ms
# Warmup Iteration   3: 8.816 ops/ms
Iteration   1: 8.895 ops/ms
Iteration   2: 8.801 ops/ms
Iteration   3: 9.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.950 ±(99.9%) 3.327 ops/ms [Average]
  (min, avg, max) = (8.801, 8.950, 9.153), stdev = 0.182
  CI (99.9%): [5.623, 12.277] (assumes normal distribution)


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
# Warmup Iteration   1: 2.513 ops/ms
# Warmup Iteration   2: 6.643 ops/ms
# Warmup Iteration   3: 7.899 ops/ms
Iteration   1: 8.204 ops/ms
Iteration   2: 8.081 ops/ms
Iteration   3: 8.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.164 ±(99.9%) 1.310 ops/ms [Average]
  (min, avg, max) = (8.081, 8.164, 8.206), stdev = 0.072
  CI (99.9%): [6.854, 9.473] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.484 ops/ms
# Warmup Iteration   2: 6.325 ops/ms
# Warmup Iteration   3: 6.993 ops/ms
Iteration   1: 7.311 ops/ms
Iteration   2: 7.432 ops/ms
Iteration   3: 7.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.416 ±(99.9%) 1.791 ops/ms [Average]
  (min, avg, max) = (7.311, 7.416, 7.505), stdev = 0.098
  CI (99.9%): [5.625, 9.207] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.812 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.012 ms/op
Iteration   1: 3.739 ±(99.9%) 0.007 ms/op
Iteration   2: 3.839 ±(99.9%) 0.004 ms/op
Iteration   3: 3.719 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.766 ±(99.9%) 1.177 ms/op [Average]
  (min, avg, max) = (3.719, 3.766, 3.839), stdev = 0.065
  CI (99.9%): [2.589, 4.943] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.979 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.004 ms/op
Iteration   1: 3.419 ±(99.9%) 0.005 ms/op
Iteration   2: 3.570 ±(99.9%) 0.004 ms/op
Iteration   3: 3.516 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.502 ±(99.9%) 1.396 ms/op [Average]
  (min, avg, max) = (3.419, 3.502, 3.570), stdev = 0.077
  CI (99.9%): [2.106, 4.898] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.458 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.699 ±(99.9%) 0.005 ms/op
Iteration   1: 3.635 ±(99.9%) 0.008 ms/op
Iteration   2: 3.493 ±(99.9%) 0.008 ms/op
Iteration   3: 3.577 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.568 ±(99.9%) 1.307 ms/op [Average]
  (min, avg, max) = (3.493, 3.568, 3.635), stdev = 0.072
  CI (99.9%): [2.261, 4.875] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.154 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.654 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.391 ±(99.9%) 0.009 ms/op
Iteration   1: 4.410 ±(99.9%) 0.016 ms/op
Iteration   2: 4.238 ±(99.9%) 0.014 ms/op
Iteration   3: 4.334 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.327 ±(99.9%) 1.568 ms/op [Average]
  (min, avg, max) = (4.238, 4.327, 4.410), stdev = 0.086
  CI (99.9%): [2.760, 5.895] (assumes normal distribution)


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
# Warmup Iteration   1: 11.340 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.017 ms/op
Iteration   1: 3.827 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.858 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   7.578 ms/op
                 createUser·p0.999:  12.468 ms/op
                 createUser·p0.9999: 23.527 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   2: 3.750 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.520 ms/op
                 createUser·p0.999:  21.594 ms/op
                 createUser·p0.9999: 26.293 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   3: 3.838 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   7.184 ms/op
                 createUser·p0.999:  26.542 ms/op
                 createUser·p0.9999: 30.070 ms/op
                 createUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 252291
  mean =      3.805 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1855 
    [ 2.500,  5.000) = 239078 
    [ 5.000,  7.500) = 9127 
    [ 7.500, 10.000) = 1407 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     21.055 ms/op
     p(99.9900) =     29.075 ms/op
     p(99.9990) =     31.242 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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
# Warmup Iteration   1: 11.095 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.011 ms/op
Iteration   1: 3.581 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  10.266 ms/op
                 existUser·p0.9999: 21.342 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   2: 3.640 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.858 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.295 ms/op
                 existUser·p0.999:  18.874 ms/op
                 existUser·p0.9999: 29.643 ms/op
                 existUser·p1.00:   31.916 ms/op

Iteration   3: 3.652 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 27.423 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 265015
  mean =      3.624 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3311 
    [ 2.500,  5.000) = 253793 
    [ 5.000,  7.500) = 6885 
    [ 7.500, 10.000) = 613 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     28.524 ms/op
     p(99.9990) =     31.424 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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
# Warmup Iteration   1: 11.259 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.013 ms/op
Iteration   1: 3.810 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.853 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.848 ms/op
                 getUser·p0.999:  22.053 ms/op
                 getUser·p0.9999: 25.513 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   2: 3.773 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.876 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.472 ms/op
                 getUser·p0.99:   6.781 ms/op
                 getUser·p0.999:  10.666 ms/op
                 getUser·p0.9999: 38.601 ms/op
                 getUser·p1.00:   39.059 ms/op

Iteration   3: 3.774 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.896 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.325 ms/op
                 getUser·p0.999:  25.494 ms/op
                 getUser·p0.9999: 32.444 ms/op
                 getUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 253520
  mean =      3.786 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1424 
    [ 2.500,  5.000) = 244499 
    [ 5.000,  7.500) = 6024 
    [ 7.500, 10.000) = 1078 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.853 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     21.577 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     38.762 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


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
# Warmup Iteration   1: 11.290 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.784 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.631 ±(99.9%) 0.017 ms/op
Iteration   1: 4.513 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.583 ms/op
                 listUser·p0.50:   4.284 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  22.682 ms/op
                 listUser·p0.9999: 27.293 ms/op
                 listUser·p1.00:   27.984 ms/op

Iteration   2: 4.405 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.042 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  16.908 ms/op
                 listUser·p0.9999: 20.889 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 4.433 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.087 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   4.883 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 22.976 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 215600
  mean =      4.450 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 195625 
    [ 5.000,  7.500) = 15919 
    [ 7.500, 10.000) = 3138 
    [10.000, 12.500) = 364 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.583 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     17.741 ms/op
     p(99.9900) =     24.929 ms/op
     p(99.9990) =     27.917 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.007 ± 2.306  ops/ms
ClientPb.existUser                       thrpt       3   8.950 ± 3.327  ops/ms
ClientPb.getUser                         thrpt       3   8.164 ± 1.310  ops/ms
ClientPb.listUser                        thrpt       3   7.416 ± 1.791  ops/ms
ClientPb.createUser                       avgt       3   3.766 ± 1.177   ms/op
ClientPb.existUser                        avgt       3   3.502 ± 1.396   ms/op
ClientPb.getUser                          avgt       3   3.568 ± 1.307   ms/op
ClientPb.listUser                         avgt       3   4.327 ± 1.568   ms/op
ClientPb.createUser                     sample  252291   3.805 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.092           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.915           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.127           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.055           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.075           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.326           ms/op
ClientPb.existUser                      sample  265015   3.624 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.372           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.969           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.463           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.140           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.524           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.916           ms/op
ClientPb.getUser                        sample  253520   3.786 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.853           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.619           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.577           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.948           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.059           ms/op
ClientPb.listUser                       sample  215600   4.450 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.583           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.964           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.741           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.929           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.984           ms/op
