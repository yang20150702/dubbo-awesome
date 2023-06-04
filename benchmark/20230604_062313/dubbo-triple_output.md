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
# Warmup Iteration   1: 2.032 ops/ms
# Warmup Iteration   2: 5.106 ops/ms
# Warmup Iteration   3: 8.531 ops/ms
Iteration   1: 8.884 ops/ms
Iteration   2: 9.056 ops/ms
Iteration   3: 8.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.901 ±(99.9%) 2.671 ops/ms [Average]
  (min, avg, max) = (8.764, 8.901, 9.056), stdev = 0.146
  CI (99.9%): [6.230, 11.572] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.047 ops/ms
# Warmup Iteration   2: 8.802 ops/ms
# Warmup Iteration   3: 9.553 ops/ms
Iteration   1: 9.815 ops/ms
Iteration   2: 9.594 ops/ms
Iteration   3: 9.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.734 ±(99.9%) 2.221 ops/ms [Average]
  (min, avg, max) = (9.594, 9.734, 9.815), stdev = 0.122
  CI (99.9%): [7.513, 11.955] (assumes normal distribution)


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
# Warmup Iteration   1: 2.832 ops/ms
# Warmup Iteration   2: 8.410 ops/ms
# Warmup Iteration   3: 9.168 ops/ms
Iteration   1: 9.666 ops/ms
Iteration   2: 9.569 ops/ms
Iteration   3: 9.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.483 ±(99.9%) 4.349 ops/ms [Average]
  (min, avg, max) = (9.213, 9.483, 9.666), stdev = 0.238
  CI (99.9%): [5.134, 13.832] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.440 ops/ms
# Warmup Iteration   2: 6.816 ops/ms
# Warmup Iteration   3: 7.922 ops/ms
Iteration   1: 7.978 ops/ms
Iteration   2: 7.851 ops/ms
Iteration   3: 7.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.896 ±(99.9%) 1.296 ops/ms [Average]
  (min, avg, max) = (7.851, 7.896, 7.978), stdev = 0.071
  CI (99.9%): [6.600, 9.192] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.424 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.706 ±(99.9%) 0.007 ms/op
Iteration   1: 3.493 ±(99.9%) 0.005 ms/op
Iteration   2: 3.445 ±(99.9%) 0.006 ms/op
Iteration   3: 3.424 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.454 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (3.424, 3.454, 3.493), stdev = 0.035
  CI (99.9%): [2.808, 4.100] (assumes normal distribution)


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
# Warmup Iteration   1: 8.067 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.005 ms/op
Iteration   1: 3.442 ±(99.9%) 0.004 ms/op
Iteration   2: 3.316 ±(99.9%) 0.004 ms/op
Iteration   3: 3.331 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.363 ±(99.9%) 1.259 ms/op [Average]
  (min, avg, max) = (3.316, 3.363, 3.442), stdev = 0.069
  CI (99.9%): [2.104, 4.622] (assumes normal distribution)


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
# Warmup Iteration   1: 9.106 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.919 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.006 ms/op
Iteration   1: 3.489 ±(99.9%) 0.004 ms/op
Iteration   2: 3.517 ±(99.9%) 0.005 ms/op
Iteration   3: 3.358 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.454 ±(99.9%) 1.548 ms/op [Average]
  (min, avg, max) = (3.358, 3.454, 3.517), stdev = 0.085
  CI (99.9%): [1.907, 5.002] (assumes normal distribution)


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
# Warmup Iteration   1: 11.193 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.355 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.143 ±(99.9%) 0.007 ms/op
Iteration   1: 4.022 ±(99.9%) 0.006 ms/op
Iteration   2: 4.077 ±(99.9%) 0.010 ms/op
Iteration   3: 3.917 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.006 ±(99.9%) 1.483 ms/op [Average]
  (min, avg, max) = (3.917, 4.006, 4.077), stdev = 0.081
  CI (99.9%): [2.522, 5.489] (assumes normal distribution)


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
# Warmup Iteration   1: 11.562 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.014 ms/op
Iteration   1: 3.643 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  19.792 ms/op
                 createUser·p0.9999: 22.467 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.442 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  21.458 ms/op
                 createUser·p0.9999: 30.015 ms/op
                 createUser·p1.00:   30.605 ms/op

Iteration   3: 3.479 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.547 ms/op
                 createUser·p0.999:  22.512 ms/op
                 createUser·p0.9999: 29.721 ms/op
                 createUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272761
  mean =      3.519 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2963 
    [ 2.500,  5.000) = 261662 
    [ 5.000,  7.500) = 6726 
    [ 7.500, 10.000) = 823 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     20.627 ms/op
     p(99.9900) =     29.712 ms/op
     p(99.9990) =     30.373 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 8.951 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.010 ms/op
Iteration   1: 3.312 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.724 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  14.500 ms/op
                 existUser·p0.9999: 24.030 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   2: 3.299 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  14.763 ms/op
                 existUser·p0.9999: 29.042 ms/op
                 existUser·p1.00:   30.605 ms/op

Iteration   3: 3.344 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.716 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  9.755 ms/op
                 existUser·p0.9999: 39.191 ms/op
                 existUser·p1.00:   40.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289160
  mean =      3.318 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 282204 
    [ 5.000, 10.000) = 6631 
    [10.000, 15.000) = 69 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 159 
    [25.000, 30.000) = 64 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     10.483 ms/op
     p(99.9900) =     37.356 ms/op
     p(99.9990) =     39.591 ms/op
     p(99.9999) =     40.567 ms/op
    p(100.0000) =     40.567 ms/op


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
# Warmup Iteration   1: 10.595 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.796 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.010 ms/op
Iteration   1: 3.438 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  20.677 ms/op
                 getUser·p0.9999: 23.967 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   2: 3.392 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  23.737 ms/op
                 getUser·p0.9999: 26.949 ms/op
                 getUser·p1.00:   27.787 ms/op

Iteration   3: 3.345 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  18.967 ms/op
                 getUser·p0.9999: 25.148 ms/op
                 getUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282842
  mean =      3.392 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3909 
    [ 2.500,  5.000) = 271211 
    [ 5.000,  7.500) = 6480 
    [ 7.500, 10.000) = 707 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 151 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     19.246 ms/op
     p(99.9900) =     25.639 ms/op
     p(99.9990) =     27.564 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 12.689 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.013 ms/op
Iteration   1: 4.056 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.901 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  23.134 ms/op
                 listUser·p0.9999: 29.335 ms/op
                 listUser·p1.00:   31.425 ms/op

Iteration   2: 4.059 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 3.939 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238956
  mean =      4.017 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 229682 
    [ 5.000,  7.500) = 6999 
    [ 7.500, 10.000) = 1410 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.901 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     24.845 ms/op
     p(99.9990) =     31.016 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.901 ± 2.671  ops/ms
ClientPb.existUser                       thrpt       3   9.734 ± 2.221  ops/ms
ClientPb.getUser                         thrpt       3   9.483 ± 4.349  ops/ms
ClientPb.listUser                        thrpt       3   7.896 ± 1.296  ops/ms
ClientPb.createUser                       avgt       3   3.454 ± 0.646   ms/op
ClientPb.existUser                        avgt       3   3.363 ± 1.259   ms/op
ClientPb.getUser                          avgt       3   3.454 ± 1.548   ms/op
ClientPb.listUser                         avgt       3   4.006 ± 1.483   ms/op
ClientPb.createUser                     sample  272761   3.519 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.044           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.627           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.712           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.605           ms/op
ClientPb.existUser                      sample  289160   3.318 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.022           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.406           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.483           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.356           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.567           ms/op
ClientPb.getUser                        sample  282842   3.392 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.087           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.246           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.639           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.787           ms/op
ClientPb.listUser                       sample  238956   4.017 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.901           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.384           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.845           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.425           ms/op
