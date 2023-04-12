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
# Warmup Iteration   1: 1.807 ops/ms
# Warmup Iteration   2: 4.471 ops/ms
# Warmup Iteration   3: 7.683 ops/ms
Iteration   1: 7.877 ops/ms
Iteration   2: 8.099 ops/ms
Iteration   3: 8.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.021 ±(99.9%) 2.277 ops/ms [Average]
  (min, avg, max) = (7.877, 8.021, 8.099), stdev = 0.125
  CI (99.9%): [5.743, 10.298] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.302 ops/ms
# Warmup Iteration   2: 7.254 ops/ms
# Warmup Iteration   3: 8.128 ops/ms
Iteration   1: 8.459 ops/ms
Iteration   2: 8.551 ops/ms
Iteration   3: 8.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.512 ±(99.9%) 0.865 ops/ms [Average]
  (min, avg, max) = (8.459, 8.512, 8.551), stdev = 0.047
  CI (99.9%): [7.647, 9.377] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.376 ops/ms
# Warmup Iteration   2: 6.487 ops/ms
# Warmup Iteration   3: 7.838 ops/ms
Iteration   1: 7.919 ops/ms
Iteration   2: 8.021 ops/ms
Iteration   3: 8.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.119 ±(99.9%) 4.797 ops/ms [Average]
  (min, avg, max) = (7.919, 8.119, 8.417), stdev = 0.263
  CI (99.9%): [3.322, 12.915] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.228 ops/ms
# Warmup Iteration   2: 6.223 ops/ms
# Warmup Iteration   3: 6.994 ops/ms
Iteration   1: 6.998 ops/ms
Iteration   2: 6.902 ops/ms
Iteration   3: 7.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.022 ±(99.9%) 2.425 ops/ms [Average]
  (min, avg, max) = (6.902, 7.022, 7.165), stdev = 0.133
  CI (99.9%): [4.597, 9.447] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.868 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.004 ms/op
Iteration   1: 3.825 ±(99.9%) 0.009 ms/op
Iteration   2: 3.670 ±(99.9%) 0.010 ms/op
Iteration   3: 3.973 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.823 ±(99.9%) 2.765 ms/op [Average]
  (min, avg, max) = (3.670, 3.823, 3.973), stdev = 0.152
  CI (99.9%): [1.058, 6.588] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.237 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.009 ms/op
Iteration   1: 3.749 ±(99.9%) 0.009 ms/op
Iteration   2: 3.731 ±(99.9%) 0.008 ms/op
Iteration   3: 3.719 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.733 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (3.719, 3.733, 3.749), stdev = 0.015
  CI (99.9%): [3.456, 4.010] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.286 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.489 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.007 ms/op
Iteration   1: 4.016 ±(99.9%) 0.009 ms/op
Iteration   2: 3.840 ±(99.9%) 0.008 ms/op
Iteration   3: 3.957 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.937 ±(99.9%) 1.637 ms/op [Average]
  (min, avg, max) = (3.840, 3.937, 4.016), stdev = 0.090
  CI (99.9%): [2.301, 5.574] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.324 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.037 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.574 ±(99.9%) 0.009 ms/op
Iteration   1: 4.412 ±(99.9%) 0.012 ms/op
Iteration   2: 4.599 ±(99.9%) 0.015 ms/op
Iteration   3: 4.355 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.456 ±(99.9%) 2.330 ms/op [Average]
  (min, avg, max) = (4.355, 4.456, 4.599), stdev = 0.128
  CI (99.9%): [2.126, 6.786] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.179 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 4.726 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.016 ms/op
Iteration   1: 3.879 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   8.331 ms/op
                 createUser·p0.999:  15.008 ms/op
                 createUser·p0.9999: 25.462 ms/op
                 createUser·p1.00:   26.870 ms/op

Iteration   2: 3.838 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.411 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  25.152 ms/op
                 createUser·p0.9999: 31.980 ms/op
                 createUser·p1.00:   32.571 ms/op

Iteration   3: 3.940 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   7.127 ms/op
                 createUser·p0.999:  14.055 ms/op
                 createUser·p0.9999: 32.287 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 246986
  mean =      3.885 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1104 
    [ 2.500,  5.000) = 233146 
    [ 5.000,  7.500) = 10767 
    [ 7.500, 10.000) = 1222 
    [10.000, 12.500) = 371 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     31.664 ms/op
     p(99.9990) =     32.753 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 12.044 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.224 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.011 ms/op
Iteration   1: 3.875 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.653 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  22.850 ms/op
                 existUser·p0.9999: 27.165 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   2: 3.820 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.796 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   5.153 ms/op
                 existUser·p0.99:   6.994 ms/op
                 existUser·p0.999:  14.483 ms/op
                 existUser·p0.9999: 27.469 ms/op
                 existUser·p1.00:   29.032 ms/op

Iteration   3: 3.770 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.159 ms/op
                 existUser·p0.999:  28.514 ms/op
                 existUser·p0.9999: 37.487 ms/op
                 existUser·p1.00:   39.322 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250968
  mean =      3.821 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 658 
    [ 2.500,  5.000) = 237463 
    [ 5.000,  7.500) = 11264 
    [ 7.500, 10.000) = 993 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     21.861 ms/op
     p(99.9900) =     35.907 ms/op
     p(99.9990) =     38.500 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


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
# Warmup Iteration   1: 11.922 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.012 ms/op
Iteration   1: 4.068 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.630 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   8.315 ms/op
                 getUser·p0.999:  23.101 ms/op
                 getUser·p0.9999: 28.054 ms/op
                 getUser·p1.00:   29.000 ms/op

Iteration   2: 3.918 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.645 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  11.420 ms/op
                 getUser·p0.9999: 27.612 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   3: 3.722 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.292 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  24.445 ms/op
                 getUser·p0.9999: 29.884 ms/op
                 getUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 246291
  mean =      3.897 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 124 
    [ 2.500,  5.000) = 235604 
    [ 5.000,  7.500) = 7556 
    [ 7.500, 10.000) = 2337 
    [10.000, 12.500) = 343 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     22.998 ms/op
     p(99.9900) =     29.110 ms/op
     p(99.9990) =     30.723 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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
# Warmup Iteration   1: 12.525 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 5.357 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.770 ±(99.9%) 0.019 ms/op
Iteration   1: 4.513 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   8.929 ms/op
                 listUser·p0.999:  22.918 ms/op
                 listUser·p0.9999: 25.982 ms/op
                 listUser·p1.00:   26.444 ms/op

Iteration   2: 4.583 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.731 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   8.524 ms/op
                 listUser·p0.999:  17.732 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 4.852 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.504 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  16.911 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206716
  mean =      4.645 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 174254 
    [ 5.000,  7.500) = 27554 
    [ 7.500, 10.000) = 3813 
    [10.000, 12.500) = 533 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     24.794 ms/op
     p(99.9990) =     26.308 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.021 ± 2.277  ops/ms
ClientPb.existUser                       thrpt       3   8.512 ± 0.865  ops/ms
ClientPb.getUser                         thrpt       3   8.119 ± 4.797  ops/ms
ClientPb.listUser                        thrpt       3   7.022 ± 2.425  ops/ms
ClientPb.createUser                       avgt       3   3.823 ± 2.765   ms/op
ClientPb.existUser                        avgt       3   3.733 ± 0.277   ms/op
ClientPb.getUser                          avgt       3   3.937 ± 1.637   ms/op
ClientPb.listUser                         avgt       3   4.456 ± 2.330   ms/op
ClientPb.createUser                     sample  246986   3.885 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.372           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.497           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.022           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.111           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.008           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.664           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.686           ms/op
ClientPb.existUser                      sample  250968   3.821 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.294           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.506           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.676           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.861           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.907           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.322           ms/op
ClientPb.getUser                        sample  246291   3.897 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.292           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.735           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.750           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.998           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.110           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.228           ms/op
ClientPb.listUser                       sample  206716   4.645 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.731           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.897           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.219           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.794           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.444           ms/op
