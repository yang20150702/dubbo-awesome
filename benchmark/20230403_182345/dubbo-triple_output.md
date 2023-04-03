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
# Warmup Iteration   1: 1.774 ops/ms
# Warmup Iteration   2: 4.236 ops/ms
# Warmup Iteration   3: 7.598 ops/ms
Iteration   1: 7.743 ops/ms
Iteration   2: 7.992 ops/ms
Iteration   3: 7.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.845 ±(99.9%) 2.381 ops/ms [Average]
  (min, avg, max) = (7.743, 7.845, 7.992), stdev = 0.130
  CI (99.9%): [5.464, 10.225] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.302 ops/ms
# Warmup Iteration   2: 6.775 ops/ms
# Warmup Iteration   3: 7.918 ops/ms
Iteration   1: 7.821 ops/ms
Iteration   2: 7.638 ops/ms
Iteration   3: 7.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.718 ±(99.9%) 1.708 ops/ms [Average]
  (min, avg, max) = (7.638, 7.718, 7.821), stdev = 0.094
  CI (99.9%): [6.010, 9.426] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.868 ops/ms
# Warmup Iteration   2: 4.565 ops/ms
# Warmup Iteration   3: 6.961 ops/ms
Iteration   1: 6.980 ops/ms
Iteration   2: 7.157 ops/ms
Iteration   3: 7.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.150 ±(99.9%) 3.033 ops/ms [Average]
  (min, avg, max) = (6.980, 7.150, 7.313), stdev = 0.166
  CI (99.9%): [4.117, 10.184] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.730 ops/ms
# Warmup Iteration   2: 4.733 ops/ms
# Warmup Iteration   3: 5.842 ops/ms
Iteration   1: 5.771 ops/ms
Iteration   2: 6.036 ops/ms
Iteration   3: 6.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.939 ±(99.9%) 2.658 ops/ms [Average]
  (min, avg, max) = (5.771, 5.939, 6.036), stdev = 0.146
  CI (99.9%): [3.281, 8.597] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 19.137 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.133 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.794 ±(99.9%) 0.012 ms/op
Iteration   1: 4.617 ±(99.9%) 0.011 ms/op
Iteration   2: 4.651 ±(99.9%) 0.012 ms/op
Iteration   3: 4.568 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.612 ±(99.9%) 0.763 ms/op [Average]
  (min, avg, max) = (4.568, 4.612, 4.651), stdev = 0.042
  CI (99.9%): [3.849, 5.375] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 16.730 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.340 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.610 ±(99.9%) 0.008 ms/op
Iteration   1: 4.413 ±(99.9%) 0.007 ms/op
Iteration   2: 4.603 ±(99.9%) 0.007 ms/op
Iteration   3: 4.462 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.492 ±(99.9%) 1.801 ms/op [Average]
  (min, avg, max) = (4.413, 4.492, 4.603), stdev = 0.099
  CI (99.9%): [2.691, 6.293] (assumes normal distribution)


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
# Warmup Iteration   1: 17.408 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.975 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.699 ±(99.9%) 0.009 ms/op
Iteration   1: 4.681 ±(99.9%) 0.006 ms/op
Iteration   2: 4.798 ±(99.9%) 0.011 ms/op
Iteration   3: 5.353 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.944 ±(99.9%) 6.556 ms/op [Average]
  (min, avg, max) = (4.681, 4.944, 5.353), stdev = 0.359
  CI (99.9%): [≈ 0, 11.500] (assumes normal distribution)


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
# Warmup Iteration   1: 19.342 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.811 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.419 ±(99.9%) 0.013 ms/op
Iteration   1: 5.214 ±(99.9%) 0.010 ms/op
Iteration   2: 5.320 ±(99.9%) 0.015 ms/op
Iteration   3: 5.310 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.281 ±(99.9%) 1.061 ms/op [Average]
  (min, avg, max) = (5.214, 5.281, 5.320), stdev = 0.058
  CI (99.9%): [4.220, 6.343] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.358 ±(99.9%) 0.241 ms/op
# Warmup Iteration   2: 6.041 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.289 ±(99.9%) 0.028 ms/op
Iteration   1: 4.649 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   4.252 ms/op
                 createUser·p0.90:   5.628 ms/op
                 createUser·p0.95:   7.247 ms/op
                 createUser·p0.99:   11.094 ms/op
                 createUser·p0.999:  25.559 ms/op
                 createUser·p0.9999: 29.255 ms/op
                 createUser·p1.00:   31.490 ms/op

Iteration   2: 4.417 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.858 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.100 ms/op
                 createUser·p0.95:   5.726 ms/op
                 createUser·p0.99:   8.194 ms/op
                 createUser·p0.999:  23.581 ms/op
                 createUser·p0.9999: 30.474 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   3: 4.486 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.046 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.333 ms/op
                 createUser·p0.95:   6.062 ms/op
                 createUser·p0.99:   8.733 ms/op
                 createUser·p0.999:  19.333 ms/op
                 createUser·p0.9999: 36.635 ms/op
                 createUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 212465
  mean =      4.516 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 181550 
    [ 5.000,  7.500) = 25222 
    [ 7.500, 10.000) = 3875 
    [10.000, 12.500) = 926 
    [12.500, 15.000) = 399 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      6.267 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     24.474 ms/op
     p(99.9900) =     34.325 ms/op
     p(99.9990) =     37.020 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.828 ±(99.9%) 0.246 ms/op
# Warmup Iteration   2: 5.421 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.483 ±(99.9%) 0.017 ms/op
Iteration   1: 4.423 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.933 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   5.980 ms/op
                 existUser·p0.99:   9.257 ms/op
                 existUser·p0.999:  25.909 ms/op
                 existUser·p0.9999: 35.031 ms/op
                 existUser·p1.00:   35.586 ms/op

Iteration   2: 4.514 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.819 ms/op
                 existUser·p0.50:   4.260 ms/op
                 existUser·p0.90:   5.382 ms/op
                 existUser·p0.95:   6.480 ms/op
                 existUser·p0.99:   10.371 ms/op
                 existUser·p0.999:  21.201 ms/op
                 existUser·p0.9999: 30.171 ms/op
                 existUser·p1.00:   30.736 ms/op

Iteration   3: 4.419 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.903 ms/op
                 existUser·p0.50:   4.182 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   6.316 ms/op
                 existUser·p0.99:   9.224 ms/op
                 existUser·p0.999:  22.697 ms/op
                 existUser·p0.9999: 31.974 ms/op
                 existUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 215532
  mean =      4.452 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 106 
    [ 2.500,  5.000) = 188869 
    [ 5.000,  7.500) = 21400 
    [ 7.500, 10.000) = 3173 
    [10.000, 12.500) = 1033 
    [12.500, 15.000) = 553 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.819 ms/op
     p(50.0000) =      4.219 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      6.242 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     24.950 ms/op
     p(99.9900) =     32.437 ms/op
     p(99.9990) =     35.535 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.375 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 5.553 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.815 ±(99.9%) 0.019 ms/op
Iteration   1: 4.816 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.757 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   6.300 ms/op
                 getUser·p0.95:   7.602 ms/op
                 getUser·p0.99:   10.971 ms/op
                 getUser·p0.999:  27.754 ms/op
                 getUser·p0.9999: 31.174 ms/op
                 getUser·p1.00:   32.440 ms/op

Iteration   2: 4.669 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.044 ms/op
                 getUser·p0.50:   4.415 ms/op
                 getUser·p0.90:   5.693 ms/op
                 getUser·p0.95:   6.471 ms/op
                 getUser·p0.99:   9.306 ms/op
                 getUser·p0.999:  17.514 ms/op
                 getUser·p0.9999: 32.211 ms/op
                 getUser·p1.00:   32.965 ms/op

Iteration   3: 4.627 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.408 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   6.636 ms/op
                 getUser·p0.99:   9.290 ms/op
                 getUser·p0.999:  19.819 ms/op
                 getUser·p0.9999: 31.442 ms/op
                 getUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 204056
  mean =      4.703 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 163235 
    [ 5.000,  7.500) = 33815 
    [ 7.500, 10.000) = 5044 
    [10.000, 12.500) = 1261 
    [12.500, 15.000) = 290 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 105 
    [30.000, 32.500) = 91 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.757 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.792 ms/op
     p(95.0000) =      6.996 ms/op
     p(99.0000) =      9.903 ms/op
     p(99.9000) =     26.886 ms/op
     p(99.9900) =     31.641 ms/op
     p(99.9990) =     32.535 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.132 ±(99.9%) 0.294 ms/op
# Warmup Iteration   2: 6.827 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 5.558 ±(99.9%) 0.026 ms/op
Iteration   1: 5.528 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   6.513 ms/op
                 listUser·p0.95:   7.815 ms/op
                 listUser·p0.99:   11.306 ms/op
                 listUser·p0.999:  28.154 ms/op
                 listUser·p0.9999: 31.661 ms/op
                 listUser·p1.00:   34.537 ms/op

Iteration   2: 5.237 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.507 ms/op
                 listUser·p0.50:   4.997 ms/op
                 listUser·p0.90:   6.046 ms/op
                 listUser·p0.95:   7.053 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  25.231 ms/op
                 listUser·p0.9999: 29.848 ms/op
                 listUser·p1.00:   30.573 ms/op

Iteration   3: 5.109 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   6.685 ms/op
                 listUser·p0.99:   9.978 ms/op
                 listUser·p0.999:  19.071 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 181295
  mean =      5.285 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 90463 
    [ 5.000,  7.500) = 83109 
    [ 7.500, 10.000) = 5386 
    [10.000, 12.500) = 1374 
    [12.500, 15.000) = 339 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.144 ms/op
     p(95.0000) =      7.160 ms/op
     p(99.0000) =     10.469 ms/op
     p(99.9000) =     25.324 ms/op
     p(99.9900) =     30.097 ms/op
     p(99.9990) =     34.165 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.845 ± 2.381  ops/ms
ClientPb.existUser                       thrpt       3   7.718 ± 1.708  ops/ms
ClientPb.getUser                         thrpt       3   7.150 ± 3.033  ops/ms
ClientPb.listUser                        thrpt       3   5.939 ± 2.658  ops/ms
ClientPb.createUser                       avgt       3   4.612 ± 0.763   ms/op
ClientPb.existUser                        avgt       3   4.492 ± 1.801   ms/op
ClientPb.getUser                          avgt       3   4.944 ± 6.556   ms/op
ClientPb.listUser                         avgt       3   5.281 ± 1.061   ms/op
ClientPb.createUser                     sample  212465   4.516 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.495           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.267           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.585           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.474           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.325           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.159           ms/op
ClientPb.existUser                      sample  215532   4.452 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.819           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.210           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.242           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.585           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.950           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.437           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.586           ms/op
ClientPb.getUser                        sample  204056   4.703 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.757           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.996           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.903           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.886           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.641           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.965           ms/op
ClientPb.listUser                       sample  181295   5.285 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.507           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.005           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.144           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.160           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.469           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.324           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.097           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.537           ms/op
