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
# Warmup Iteration   1: 2.589 ops/ms
# Warmup Iteration   2: 5.999 ops/ms
# Warmup Iteration   3: 9.083 ops/ms
Iteration   1: 9.432 ops/ms
Iteration   2: 10.032 ops/ms
Iteration   3: 9.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.789 ±(99.9%) 5.768 ops/ms [Average]
  (min, avg, max) = (9.432, 9.789, 10.032), stdev = 0.316
  CI (99.9%): [4.021, 15.558] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.370 ops/ms
# Warmup Iteration   2: 9.457 ops/ms
# Warmup Iteration   3: 10.232 ops/ms
Iteration   1: 10.210 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.505 ±(99.9%) 4.939 ops/ms [Average]
  (min, avg, max) = (10.210, 10.505, 10.741), stdev = 0.271
  CI (99.9%): [5.567, 15.444] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.463 ops/ms
# Warmup Iteration   2: 9.357 ops/ms
# Warmup Iteration   3: 9.948 ops/ms
Iteration   1: 10.410 ops/ms
Iteration   2: 10.318 ops/ms
Iteration   3: 10.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.347 ±(99.9%) 1.000 ops/ms [Average]
  (min, avg, max) = (10.313, 10.347, 10.410), stdev = 0.055
  CI (99.9%): [9.347, 11.347] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.219 ops/ms
# Warmup Iteration   2: 7.758 ops/ms
# Warmup Iteration   3: 8.235 ops/ms
Iteration   1: 8.670 ops/ms
Iteration   2: 8.562 ops/ms
Iteration   3: 8.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.590 ±(99.9%) 1.282 ops/ms [Average]
  (min, avg, max) = (8.538, 8.590, 8.670), stdev = 0.070
  CI (99.9%): [7.308, 9.872] (assumes normal distribution)


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
# Warmup Iteration   1: 7.736 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.005 ms/op
Iteration   1: 3.184 ±(99.9%) 0.009 ms/op
Iteration   2: 3.264 ±(99.9%) 0.004 ms/op
Iteration   3: 3.066 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.171 ±(99.9%) 1.817 ms/op [Average]
  (min, avg, max) = (3.066, 3.171, 3.264), stdev = 0.100
  CI (99.9%): [1.354, 4.989] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.806 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.003 ms/op
Iteration   1: 3.071 ±(99.9%) 0.005 ms/op
Iteration   2: 3.222 ±(99.9%) 0.008 ms/op
Iteration   3: 3.186 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.159 ±(99.9%) 1.438 ms/op [Average]
  (min, avg, max) = (3.071, 3.159, 3.222), stdev = 0.079
  CI (99.9%): [1.721, 4.598] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.464 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.409 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.003 ms/op
Iteration   1: 3.206 ±(99.9%) 0.005 ms/op
Iteration   2: 3.296 ±(99.9%) 0.006 ms/op
Iteration   3: 3.349 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.284 ±(99.9%) 1.319 ms/op [Average]
  (min, avg, max) = (3.206, 3.284, 3.349), stdev = 0.072
  CI (99.9%): [1.964, 4.603] (assumes normal distribution)


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
# Warmup Iteration   1: 10.328 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.244 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.007 ms/op
Iteration   1: 3.813 ±(99.9%) 0.010 ms/op
Iteration   2: 3.948 ±(99.9%) 0.008 ms/op
Iteration   3: 3.734 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.832 ±(99.9%) 1.970 ms/op [Average]
  (min, avg, max) = (3.734, 3.832, 3.948), stdev = 0.108
  CI (99.9%): [1.862, 5.802] (assumes normal distribution)


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
# Warmup Iteration   1: 9.201 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.010 ms/op
Iteration   1: 3.123 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  10.309 ms/op
                 createUser·p0.9999: 21.390 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   2: 3.225 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  20.663 ms/op
                 createUser·p0.9999: 22.907 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.642 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  15.589 ms/op
                 createUser·p0.9999: 26.937 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301113
  mean =      3.186 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23323 
    [ 2.500,  5.000) = 273847 
    [ 5.000,  7.500) = 3216 
    [ 7.500, 10.000) = 359 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 181 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     24.081 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 7.409 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.007 ms/op
Iteration   1: 3.052 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.318 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  9.750 ms/op
                 existUser·p0.9999: 19.875 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.677 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  12.018 ms/op
                 existUser·p0.9999: 22.405 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   3: 3.096 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.391 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  10.273 ms/op
                 existUser·p0.9999: 20.120 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309361
  mean =      3.102 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25425 
    [ 2.500,  5.000) = 279108 
    [ 5.000,  7.500) = 4143 
    [ 7.500, 10.000) = 316 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 192 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.269 ms/op
     p(95.0000) =      3.449 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     11.439 ms/op
     p(99.9900) =     21.236 ms/op
     p(99.9990) =     22.857 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 8.595 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.009 ms/op
Iteration   1: 3.198 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.538 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  18.022 ms/op
                 getUser·p0.9999: 20.250 ms/op
                 getUser·p1.00:   21.037 ms/op

Iteration   2: 3.136 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  9.748 ms/op
                 getUser·p0.9999: 22.852 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   3: 3.192 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.898 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.970 ms/op
                 getUser·p0.999:  9.411 ms/op
                 getUser·p0.9999: 22.341 ms/op
                 getUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302283
  mean =      3.175 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17340 
    [ 2.500,  5.000) = 279231 
    [ 5.000,  7.500) = 4684 
    [ 7.500, 10.000) = 628 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     17.217 ms/op
     p(99.9900) =     22.176 ms/op
     p(99.9990) =     23.428 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 9.696 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.449 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.014 ms/op
Iteration   1: 3.839 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.011 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  17.930 ms/op
                 listUser·p0.9999: 28.005 ms/op
                 listUser·p1.00:   28.869 ms/op

Iteration   2: 3.806 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.684 ms/op
                 listUser·p0.999:  14.156 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   3: 3.649 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.017 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   4.076 ms/op
                 listUser·p0.99:   6.038 ms/op
                 listUser·p0.999:  13.009 ms/op
                 listUser·p0.9999: 17.367 ms/op
                 listUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254960
  mean =      3.763 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 247718 
    [ 5.000,  7.500) = 5590 
    [ 7.500, 10.000) = 1000 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     26.362 ms/op
     p(99.9990) =     28.359 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.789 ± 5.768  ops/ms
ClientPb.existUser                       thrpt       3  10.505 ± 4.939  ops/ms
ClientPb.getUser                         thrpt       3  10.347 ± 1.000  ops/ms
ClientPb.listUser                        thrpt       3   8.590 ± 1.282  ops/ms
ClientPb.createUser                       avgt       3   3.171 ± 1.817   ms/op
ClientPb.existUser                        avgt       3   3.159 ± 1.438   ms/op
ClientPb.getUser                          avgt       3   3.284 ± 1.319   ms/op
ClientPb.listUser                         avgt       3   3.832 ± 1.970   ms/op
ClientPb.createUser                     sample  301113   3.186 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.348           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.038           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.081           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.165           ms/op
ClientPb.existUser                      sample  309361   3.102 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.473           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.449           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.439           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.236           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.134           ms/op
ClientPb.getUser                        sample  302283   3.175 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.614           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.502           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.874           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.217           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.176           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.593           ms/op
ClientPb.listUser                       sample  254960   3.763 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.011           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.729           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.362           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.869           ms/op
