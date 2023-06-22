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
# Warmup Iteration   1: 2.189 ops/ms
# Warmup Iteration   2: 6.137 ops/ms
# Warmup Iteration   3: 8.898 ops/ms
Iteration   1: 9.076 ops/ms
Iteration   2: 9.440 ops/ms
Iteration   3: 9.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.287 ±(99.9%) 3.451 ops/ms [Average]
  (min, avg, max) = (9.076, 9.287, 9.440), stdev = 0.189
  CI (99.9%): [5.836, 12.739] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.389 ops/ms
# Warmup Iteration   2: 8.770 ops/ms
# Warmup Iteration   3: 9.523 ops/ms
Iteration   1: 9.298 ops/ms
Iteration   2: 9.411 ops/ms
Iteration   3: 9.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.432 ±(99.9%) 2.656 ops/ms [Average]
  (min, avg, max) = (9.298, 9.432, 9.587), stdev = 0.146
  CI (99.9%): [6.776, 12.088] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.155 ops/ms
# Warmup Iteration   2: 8.610 ops/ms
# Warmup Iteration   3: 9.451 ops/ms
Iteration   1: 9.388 ops/ms
Iteration   2: 9.337 ops/ms
Iteration   3: 9.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.400 ±(99.9%) 1.270 ops/ms [Average]
  (min, avg, max) = (9.337, 9.400, 9.474), stdev = 0.070
  CI (99.9%): [8.130, 10.670] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.168 ops/ms
# Warmup Iteration   2: 7.641 ops/ms
# Warmup Iteration   3: 7.716 ops/ms
Iteration   1: 8.027 ops/ms
Iteration   2: 7.891 ops/ms
Iteration   3: 8.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.055 ±(99.9%) 3.272 ops/ms [Average]
  (min, avg, max) = (7.891, 8.055, 8.246), stdev = 0.179
  CI (99.9%): [4.783, 11.327] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 11.122 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.801 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.005 ms/op
Iteration   1: 3.410 ±(99.9%) 0.008 ms/op
Iteration   2: 3.336 ±(99.9%) 0.006 ms/op
Iteration   3: 3.257 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.334 ±(99.9%) 1.394 ms/op [Average]
  (min, avg, max) = (3.257, 3.334, 3.410), stdev = 0.076
  CI (99.9%): [1.940, 4.728] (assumes normal distribution)


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
# Warmup Iteration   1: 8.529 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.008 ms/op
Iteration   1: 3.268 ±(99.9%) 0.008 ms/op
Iteration   2: 3.233 ±(99.9%) 0.005 ms/op
Iteration   3: 3.348 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.283 ±(99.9%) 1.079 ms/op [Average]
  (min, avg, max) = (3.233, 3.283, 3.348), stdev = 0.059
  CI (99.9%): [2.204, 4.362] (assumes normal distribution)


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
# Warmup Iteration   1: 9.237 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.003 ms/op
Iteration   1: 3.506 ±(99.9%) 0.004 ms/op
Iteration   2: 3.414 ±(99.9%) 0.009 ms/op
Iteration   3: 3.350 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.423 ±(99.9%) 1.435 ms/op [Average]
  (min, avg, max) = (3.350, 3.423, 3.506), stdev = 0.079
  CI (99.9%): [1.988, 4.859] (assumes normal distribution)


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
# Warmup Iteration   1: 9.955 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.010 ms/op
Iteration   1: 4.027 ±(99.9%) 0.009 ms/op
Iteration   2: 4.061 ±(99.9%) 0.013 ms/op
Iteration   3: 3.912 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.000 ±(99.9%) 1.426 ms/op [Average]
  (min, avg, max) = (3.912, 4.000, 4.061), stdev = 0.078
  CI (99.9%): [2.574, 5.426] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.930 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.010 ms/op
Iteration   1: 3.446 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  19.246 ms/op
                 createUser·p0.9999: 23.715 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   2: 3.522 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  22.446 ms/op
                 createUser·p0.9999: 30.242 ms/op
                 createUser·p1.00:   31.293 ms/op

Iteration   3: 3.415 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  21.429 ms/op
                 createUser·p0.9999: 27.317 ms/op
                 createUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277337
  mean =      3.461 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7208 
    [ 2.500,  5.000) = 264345 
    [ 5.000,  7.500) = 4856 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     29.622 ms/op
     p(99.9990) =     30.610 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 7.033 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.007 ms/op
Iteration   1: 3.274 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.716 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  11.277 ms/op
                 existUser·p0.9999: 22.388 ms/op
                 existUser·p1.00:   23.724 ms/op

Iteration   2: 3.355 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.612 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  13.588 ms/op
                 existUser·p0.9999: 27.195 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   3: 3.401 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.333 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  18.024 ms/op
                 existUser·p0.9999: 28.213 ms/op
                 existUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286998
  mean =      3.342 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19212 
    [ 2.500,  5.000) = 262417 
    [ 5.000,  7.500) = 4499 
    [ 7.500, 10.000) = 464 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      0.333 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     26.922 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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
# Warmup Iteration   1: 9.799 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.008 ms/op
Iteration   1: 3.542 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.747 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  17.389 ms/op
                 getUser·p0.9999: 21.167 ms/op
                 getUser·p1.00:   22.217 ms/op

Iteration   2: 3.422 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  19.828 ms/op
                 getUser·p0.9999: 37.721 ms/op
                 getUser·p1.00:   38.273 ms/op

Iteration   3: 3.533 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  16.024 ms/op
                 getUser·p0.9999: 23.167 ms/op
                 getUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274370
  mean =      3.498 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2889 
    [ 2.500,  5.000) = 263758 
    [ 5.000,  7.500) = 6579 
    [ 7.500, 10.000) = 698 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     16.712 ms/op
     p(99.9900) =     36.504 ms/op
     p(99.9990) =     38.207 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


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
# Warmup Iteration   1: 9.130 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.263 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.012 ms/op
Iteration   1: 4.007 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  21.266 ms/op
                 listUser·p0.9999: 22.971 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   2: 3.889 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 4.030 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  15.429 ms/op
                 listUser·p0.9999: 17.465 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241302
  mean =      3.974 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 231703 
    [ 5.000,  7.500) = 7207 
    [ 7.500, 10.000) = 1410 
    [10.000, 12.500) = 392 
    [12.500, 15.000) = 299 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.118 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     15.194 ms/op
     p(99.9900) =     22.728 ms/op
     p(99.9990) =     23.842 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.287 ± 3.451  ops/ms
ClientPb.existUser                       thrpt       3   9.432 ± 2.656  ops/ms
ClientPb.getUser                         thrpt       3   9.400 ± 1.270  ops/ms
ClientPb.listUser                        thrpt       3   8.055 ± 3.272  ops/ms
ClientPb.createUser                       avgt       3   3.334 ± 1.394   ms/op
ClientPb.existUser                        avgt       3   3.283 ± 1.079   ms/op
ClientPb.getUser                          avgt       3   3.423 ± 1.435   ms/op
ClientPb.listUser                         avgt       3   4.000 ± 1.426   ms/op
ClientPb.createUser                     sample  277337   3.461 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.775           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.054           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.622           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.293           ms/op
ClientPb.existUser                      sample  286998   3.342 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.333           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.505           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.615           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.922           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.541           ms/op
ClientPb.getUser                        sample  274370   3.498 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.145           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.365           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.712           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.504           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.273           ms/op
ClientPb.listUser                       sample  241302   3.974 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.118           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.463           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.194           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.728           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.888           ms/op
