# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.326 ops/ms
# Warmup Iteration   2: 5.634 ops/ms
# Warmup Iteration   3: 8.594 ops/ms
Iteration   1: 9.550 ops/ms
Iteration   2: 9.480 ops/ms
Iteration   3: 9.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.438 ±(99.9%) 2.516 ops/ms [Average]
  (min, avg, max) = (9.284, 9.438, 9.550), stdev = 0.138
  CI (99.9%): [6.923, 11.954] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.336 ops/ms
# Warmup Iteration   2: 8.740 ops/ms
# Warmup Iteration   3: 9.619 ops/ms
Iteration   1: 9.872 ops/ms
Iteration   2: 9.942 ops/ms
Iteration   3: 9.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.923 ±(99.9%) 0.804 ops/ms [Average]
  (min, avg, max) = (9.872, 9.923, 9.954), stdev = 0.044
  CI (99.9%): [9.119, 10.726] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.332 ops/ms
# Warmup Iteration   2: 8.651 ops/ms
# Warmup Iteration   3: 9.014 ops/ms
Iteration   1: 9.557 ops/ms
Iteration   2: 9.331 ops/ms
Iteration   3: 9.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.560 ±(99.9%) 4.208 ops/ms [Average]
  (min, avg, max) = (9.331, 9.560, 9.792), stdev = 0.231
  CI (99.9%): [5.352, 13.768] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.966 ops/ms
# Warmup Iteration   2: 7.433 ops/ms
# Warmup Iteration   3: 8.076 ops/ms
Iteration   1: 8.024 ops/ms
Iteration   2: 8.127 ops/ms
Iteration   3: 8.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.150 ±(99.9%) 2.530 ops/ms [Average]
  (min, avg, max) = (8.024, 8.150, 8.299), stdev = 0.139
  CI (99.9%): [5.620, 10.680] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.921 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.006 ms/op
Iteration   1: 3.244 ±(99.9%) 0.012 ms/op
Iteration   2: 3.269 ±(99.9%) 0.009 ms/op
Iteration   3: 3.305 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.273 ±(99.9%) 0.557 ms/op [Average]
  (min, avg, max) = (3.244, 3.273, 3.305), stdev = 0.031
  CI (99.9%): [2.716, 3.830] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.298 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.520 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.003 ms/op
Iteration   1: 3.256 ±(99.9%) 0.004 ms/op
Iteration   2: 3.200 ±(99.9%) 0.004 ms/op
Iteration   3: 3.248 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.235 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (3.200, 3.235, 3.256), stdev = 0.031
  CI (99.9%): [2.676, 3.794] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.926 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.004 ms/op
Iteration   1: 3.354 ±(99.9%) 0.010 ms/op
Iteration   2: 3.418 ±(99.9%) 0.003 ms/op
Iteration   3: 3.438 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.403 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (3.354, 3.403, 3.438), stdev = 0.044
  CI (99.9%): [2.603, 4.204] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.723 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.491 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.010 ms/op
Iteration   1: 3.881 ±(99.9%) 0.011 ms/op
Iteration   2: 3.866 ±(99.9%) 0.009 ms/op
Iteration   3: 3.829 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.859 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (3.829, 3.859, 3.881), stdev = 0.027
  CI (99.9%): [3.365, 4.353] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.360 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.010 ms/op
Iteration   1: 3.303 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  18.588 ms/op
                 createUser·p0.9999: 24.281 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   2: 3.436 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.738 ms/op
                 createUser·p0.999:  21.592 ms/op
                 createUser·p0.9999: 25.519 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   3: 3.426 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.357 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  19.381 ms/op
                 createUser·p0.9999: 28.071 ms/op
                 createUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283483
  mean =      3.387 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11679 
    [ 2.500,  5.000) = 263393 
    [ 5.000,  7.500) = 7342 
    [ 7.500, 10.000) = 524 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     19.448 ms/op
     p(99.9900) =     26.998 ms/op
     p(99.9990) =     29.081 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.701 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.008 ms/op
Iteration   1: 3.210 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  10.863 ms/op
                 existUser·p0.9999: 22.780 ms/op
                 existUser·p1.00:   23.429 ms/op

Iteration   2: 3.161 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.799 ms/op
                 existUser·p0.999:  12.632 ms/op
                 existUser·p0.9999: 25.718 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   3: 3.157 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.696 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.657 ms/op
                 existUser·p0.999:  13.100 ms/op
                 existUser·p0.9999: 22.872 ms/op
                 existUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302464
  mean =      3.176 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6647 
    [ 2.500,  5.000) = 291946 
    [ 5.000,  7.500) = 2781 
    [ 7.500, 10.000) = 649 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     26.473 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.051 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.010 ms/op
Iteration   1: 3.412 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  21.577 ms/op
                 getUser·p0.9999: 29.086 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   2: 3.351 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  8.847 ms/op
                 getUser·p0.9999: 25.803 ms/op
                 getUser·p1.00:   26.870 ms/op

Iteration   3: 3.369 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.366 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  18.751 ms/op
                 getUser·p0.9999: 26.346 ms/op
                 getUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284142
  mean =      3.377 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3486 
    [ 2.500,  5.000) = 272041 
    [ 5.000,  7.500) = 7393 
    [ 7.500, 10.000) = 722 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     13.627 ms/op
     p(99.9900) =     27.615 ms/op
     p(99.9990) =     29.705 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.864 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.013 ms/op
Iteration   1: 3.929 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  21.594 ms/op
                 listUser·p0.9999: 24.211 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   2: 4.004 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.058 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  15.485 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 3.966 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.460 ms/op
                 listUser·p0.999:  15.041 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242082
  mean =      3.966 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 232208 
    [ 5.000,  7.500) = 7582 
    [ 7.500, 10.000) = 1463 
    [10.000, 12.500) = 274 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     23.390 ms/op
     p(99.9990) =     24.974 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.438 ± 2.516  ops/ms
ClientPb.existUser                       thrpt       3   9.923 ± 0.804  ops/ms
ClientPb.getUser                         thrpt       3   9.560 ± 4.208  ops/ms
ClientPb.listUser                        thrpt       3   8.150 ± 2.530  ops/ms
ClientPb.createUser                       avgt       3   3.273 ± 0.557   ms/op
ClientPb.existUser                        avgt       3   3.235 ± 0.559   ms/op
ClientPb.getUser                          avgt       3   3.403 ± 0.801   ms/op
ClientPb.listUser                         avgt       3   3.859 ± 0.494   ms/op
ClientPb.createUser                     sample  283483   3.387 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.357           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.931           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.448           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.998           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.721           ms/op
ClientPb.existUser                      sample  302464   3.176 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.047           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.457           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.497           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.632           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.707           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.771           ms/op
ClientPb.getUser                        sample  284142   3.377 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.790           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.357           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.627           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.615           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.179           ms/op
ClientPb.listUser                       sample  242082   3.966 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.638           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.768           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.365           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.958           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.390           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.231           ms/op
