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
# Warmup Iteration   1: 2.171 ops/ms
# Warmup Iteration   2: 4.522 ops/ms
# Warmup Iteration   3: 8.263 ops/ms
Iteration   1: 9.024 ops/ms
Iteration   2: 9.262 ops/ms
Iteration   3: 9.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.288 ±(99.9%) 5.066 ops/ms [Average]
  (min, avg, max) = (9.024, 9.288, 9.578), stdev = 0.278
  CI (99.9%): [4.222, 14.354] (assumes normal distribution)


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
# Warmup Iteration   1: 3.244 ops/ms
# Warmup Iteration   2: 8.615 ops/ms
# Warmup Iteration   3: 9.384 ops/ms
Iteration   1: 9.784 ops/ms
Iteration   2: 9.859 ops/ms
Iteration   3: 9.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.826 ±(99.9%) 0.700 ops/ms [Average]
  (min, avg, max) = (9.784, 9.826, 9.859), stdev = 0.038
  CI (99.9%): [9.126, 10.526] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.069 ops/ms
# Warmup Iteration   2: 8.395 ops/ms
# Warmup Iteration   3: 8.997 ops/ms
Iteration   1: 9.347 ops/ms
Iteration   2: 9.236 ops/ms
Iteration   3: 9.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.324 ±(99.9%) 1.429 ops/ms [Average]
  (min, avg, max) = (9.236, 9.324, 9.388), stdev = 0.078
  CI (99.9%): [7.895, 10.753] (assumes normal distribution)


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
# Warmup Iteration   1: 2.901 ops/ms
# Warmup Iteration   2: 7.197 ops/ms
# Warmup Iteration   3: 7.874 ops/ms
Iteration   1: 7.902 ops/ms
Iteration   2: 8.169 ops/ms
Iteration   3: 7.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.933 ±(99.9%) 4.060 ops/ms [Average]
  (min, avg, max) = (7.727, 7.933, 8.169), stdev = 0.223
  CI (99.9%): [3.873, 11.993] (assumes normal distribution)


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
# Warmup Iteration   1: 9.461 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.663 ±(99.9%) 0.006 ms/op
Iteration   1: 3.525 ±(99.9%) 0.004 ms/op
Iteration   2: 3.460 ±(99.9%) 0.008 ms/op
Iteration   3: 3.538 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.508 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (3.460, 3.508, 3.538), stdev = 0.042
  CI (99.9%): [2.749, 4.267] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.629 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.004 ms/op
Iteration   1: 3.225 ±(99.9%) 0.003 ms/op
Iteration   2: 3.223 ±(99.9%) 0.004 ms/op
Iteration   3: 3.231 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.226 ±(99.9%) 0.077 ms/op [Average]
  (min, avg, max) = (3.223, 3.226, 3.231), stdev = 0.004
  CI (99.9%): [3.149, 3.303] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.004 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.646 ±(99.9%) 0.004 ms/op
Iteration   1: 3.456 ±(99.9%) 0.010 ms/op
Iteration   2: 3.423 ±(99.9%) 0.007 ms/op
Iteration   3: 3.355 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.411 ±(99.9%) 0.943 ms/op [Average]
  (min, avg, max) = (3.355, 3.411, 3.456), stdev = 0.052
  CI (99.9%): [2.468, 4.354] (assumes normal distribution)


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
# Warmup Iteration   1: 11.212 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.009 ms/op
Iteration   1: 3.933 ±(99.9%) 0.012 ms/op
Iteration   2: 3.825 ±(99.9%) 0.016 ms/op
Iteration   3: 4.120 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.959 ±(99.9%) 2.723 ms/op [Average]
  (min, avg, max) = (3.825, 3.959, 4.120), stdev = 0.149
  CI (99.9%): [1.237, 6.682] (assumes normal distribution)


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
# Warmup Iteration   1: 8.923 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.010 ms/op
Iteration   1: 3.456 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  21.101 ms/op
                 createUser·p0.9999: 24.928 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   2: 3.523 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  20.724 ms/op
                 createUser·p0.9999: 26.673 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   3: 3.444 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.198 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  17.828 ms/op
                 createUser·p0.9999: 24.992 ms/op
                 createUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276130
  mean =      3.474 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10895 
    [ 2.500,  5.000) = 258267 
    [ 5.000,  7.500) = 5737 
    [ 7.500, 10.000) = 796 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     25.899 ms/op
     p(99.9990) =     26.940 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.638 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.008 ms/op
Iteration   1: 3.233 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  12.060 ms/op
                 existUser·p0.9999: 22.274 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.364 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.097 ms/op
                 existUser·p0.999:  14.882 ms/op
                 existUser·p0.9999: 27.384 ms/op
                 existUser·p1.00:   29.000 ms/op

Iteration   3: 3.364 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.058 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  17.937 ms/op
                 existUser·p0.9999: 25.032 ms/op
                 existUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292149
  mean =      3.285 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14328 
    [ 2.500,  5.000) = 273513 
    [ 5.000,  7.500) = 3552 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 150 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     13.124 ms/op
     p(99.9900) =     24.445 ms/op
     p(99.9990) =     28.637 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 8.295 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.010 ms/op
Iteration   1: 3.496 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   6.922 ms/op
                 getUser·p0.999:  20.530 ms/op
                 getUser·p0.9999: 23.658 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   2: 3.464 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.845 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  10.235 ms/op
                 getUser·p0.9999: 25.322 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   3: 3.518 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  18.985 ms/op
                 getUser·p0.9999: 26.048 ms/op
                 getUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274654
  mean =      3.492 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6735 
    [ 2.500,  5.000) = 258311 
    [ 5.000,  7.500) = 8275 
    [ 7.500, 10.000) = 830 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.492 ms/op
     p(99.9000) =     16.417 ms/op
     p(99.9900) =     25.347 ms/op
     p(99.9990) =     26.789 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 11.896 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.251 ±(99.9%) 0.015 ms/op
Iteration   1: 4.004 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  20.353 ms/op
                 listUser·p0.9999: 23.331 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   2: 3.829 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.526 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 16.663 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 3.969 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.484 ms/op
                 listUser·p0.999:  15.245 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243869
  mean =      3.933 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 235728 
    [ 5.000,  7.500) = 5920 
    [ 7.500, 10.000) = 1353 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.318 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     22.650 ms/op
     p(99.9990) =     25.010 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.288 ± 5.066  ops/ms
ClientPb.existUser                       thrpt       3   9.826 ± 0.700  ops/ms
ClientPb.getUser                         thrpt       3   9.324 ± 1.429  ops/ms
ClientPb.listUser                        thrpt       3   7.933 ± 4.060  ops/ms
ClientPb.createUser                       avgt       3   3.508 ± 0.759   ms/op
ClientPb.existUser                        avgt       3   3.226 ± 0.077   ms/op
ClientPb.getUser                          avgt       3   3.411 ± 0.943   ms/op
ClientPb.listUser                         avgt       3   3.959 ± 2.723   ms/op
ClientPb.createUser                     sample  276130   3.474 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.847           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.267           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.416           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.899           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.230           ms/op
ClientPb.existUser                      sample  292149   3.285 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.176           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.124           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.445           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.000           ms/op
ClientPb.getUser                        sample  274654   3.492 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.019           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.492           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.417           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.347           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.935           ms/op
ClientPb.listUser                       sample  243869   3.933 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.526           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.318           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.237           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.650           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.919           ms/op
