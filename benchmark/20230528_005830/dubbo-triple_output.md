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
# Warmup Iteration   1: 2.257 ops/ms
# Warmup Iteration   2: 5.962 ops/ms
# Warmup Iteration   3: 8.664 ops/ms
Iteration   1: 9.386 ops/ms
Iteration   2: 9.381 ops/ms
Iteration   3: 9.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.323 ±(99.9%) 1.912 ops/ms [Average]
  (min, avg, max) = (9.202, 9.323, 9.386), stdev = 0.105
  CI (99.9%): [7.411, 11.235] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.094 ops/ms
# Warmup Iteration   2: 8.819 ops/ms
# Warmup Iteration   3: 9.647 ops/ms
Iteration   1: 9.672 ops/ms
Iteration   2: 9.557 ops/ms
Iteration   3: 10.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.743 ±(99.9%) 4.204 ops/ms [Average]
  (min, avg, max) = (9.557, 9.743, 10.001), stdev = 0.230
  CI (99.9%): [5.539, 13.947] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.831 ops/ms
# Warmup Iteration   2: 8.592 ops/ms
# Warmup Iteration   3: 9.554 ops/ms
Iteration   1: 9.015 ops/ms
Iteration   2: 9.187 ops/ms
Iteration   3: 8.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.018 ±(99.9%) 3.068 ops/ms [Average]
  (min, avg, max) = (8.851, 9.018, 9.187), stdev = 0.168
  CI (99.9%): [5.949, 12.086] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.777 ops/ms
# Warmup Iteration   2: 7.265 ops/ms
# Warmup Iteration   3: 7.789 ops/ms
Iteration   1: 8.134 ops/ms
Iteration   2: 7.993 ops/ms
Iteration   3: 8.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.149 ±(99.9%) 2.998 ops/ms [Average]
  (min, avg, max) = (7.993, 8.149, 8.321), stdev = 0.164
  CI (99.9%): [5.151, 11.148] (assumes normal distribution)


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
# Warmup Iteration   1: 9.442 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.006 ms/op
Iteration   1: 3.458 ±(99.9%) 0.010 ms/op
Iteration   2: 3.428 ±(99.9%) 0.005 ms/op
Iteration   3: 3.246 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.377 ±(99.9%) 2.085 ms/op [Average]
  (min, avg, max) = (3.246, 3.377, 3.458), stdev = 0.114
  CI (99.9%): [1.292, 5.463] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.321 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.587 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.002 ms/op
Iteration   1: 3.299 ±(99.9%) 0.005 ms/op
Iteration   2: 3.333 ±(99.9%) 0.009 ms/op
Iteration   3: 3.492 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.374 ±(99.9%) 1.879 ms/op [Average]
  (min, avg, max) = (3.299, 3.374, 3.492), stdev = 0.103
  CI (99.9%): [1.496, 5.253] (assumes normal distribution)


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
# Warmup Iteration   1: 8.900 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.007 ms/op
Iteration   1: 3.461 ±(99.9%) 0.009 ms/op
Iteration   2: 3.315 ±(99.9%) 0.005 ms/op
Iteration   3: 3.357 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.378 ±(99.9%) 1.372 ms/op [Average]
  (min, avg, max) = (3.315, 3.378, 3.461), stdev = 0.075
  CI (99.9%): [2.005, 4.750] (assumes normal distribution)


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
# Warmup Iteration   1: 9.995 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.012 ms/op
Iteration   1: 3.828 ±(99.9%) 0.013 ms/op
Iteration   2: 3.902 ±(99.9%) 0.010 ms/op
Iteration   3: 3.921 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.883 ±(99.9%) 0.893 ms/op [Average]
  (min, avg, max) = (3.828, 3.883, 3.921), stdev = 0.049
  CI (99.9%): [2.990, 4.776] (assumes normal distribution)


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
# Warmup Iteration   1: 9.429 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.010 ms/op
Iteration   1: 3.447 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.885 ms/op
                 createUser·p0.999:  23.438 ms/op
                 createUser·p0.9999: 29.646 ms/op
                 createUser·p1.00:   30.212 ms/op

Iteration   2: 3.450 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  22.886 ms/op
                 createUser·p0.9999: 25.484 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   3: 3.417 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.270 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  18.294 ms/op
                 createUser·p0.9999: 35.531 ms/op
                 createUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279316
  mean =      3.438 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8759 
    [ 2.500,  5.000) = 264444 
    [ 5.000,  7.500) = 4901 
    [ 7.500, 10.000) = 604 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     18.864 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 8.016 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
Iteration   1: 3.273 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  15.631 ms/op
                 existUser·p0.9999: 25.909 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   2: 3.190 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  10.695 ms/op
                 existUser·p0.9999: 27.066 ms/op
                 existUser·p1.00:   28.934 ms/op

Iteration   3: 3.398 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  18.607 ms/op
                 existUser·p0.9999: 27.656 ms/op
                 existUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292056
  mean =      3.285 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12158 
    [ 2.500,  5.000) = 275494 
    [ 5.000,  7.500) = 3577 
    [ 7.500, 10.000) = 381 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 76 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     14.625 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 8.453 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.009 ms/op
Iteration   1: 3.487 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.604 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.998 ms/op
                 getUser·p0.999:  13.773 ms/op
                 getUser·p0.9999: 23.653 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   2: 3.418 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  22.149 ms/op
                 getUser·p0.9999: 28.256 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   3: 3.417 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.616 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  23.783 ms/op
                 getUser·p0.9999: 26.301 ms/op
                 getUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278817
  mean =      3.441 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5628 
    [ 2.500,  5.000) = 265416 
    [ 5.000,  7.500) = 6447 
    [ 7.500, 10.000) = 797 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     13.892 ms/op
     p(99.9900) =     26.812 ms/op
     p(99.9990) =     28.955 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 10.192 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.014 ms/op
Iteration   1: 3.989 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  18.081 ms/op
                 listUser·p0.9999: 27.524 ms/op
                 listUser·p1.00:   29.000 ms/op

Iteration   2: 3.938 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  18.232 ms/op
                 listUser·p0.9999: 20.511 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   3: 3.933 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  15.450 ms/op
                 listUser·p0.9999: 16.693 ms/op
                 listUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242818
  mean =      3.953 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 234112 
    [ 5.000,  7.500) = 6741 
    [ 7.500, 10.000) = 1194 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     16.534 ms/op
     p(99.9900) =     25.817 ms/op
     p(99.9990) =     28.845 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.323 ± 1.912  ops/ms
ClientPb.existUser                       thrpt       3   9.743 ± 4.204  ops/ms
ClientPb.getUser                         thrpt       3   9.018 ± 3.068  ops/ms
ClientPb.listUser                        thrpt       3   8.149 ± 2.998  ops/ms
ClientPb.createUser                       avgt       3   3.377 ± 2.085   ms/op
ClientPb.existUser                        avgt       3   3.374 ± 1.879   ms/op
ClientPb.getUser                          avgt       3   3.378 ± 1.372   ms/op
ClientPb.listUser                         avgt       3   3.883 ± 0.893   ms/op
ClientPb.createUser                     sample  279316   3.438 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.184           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.137           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.808           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.864           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.144           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.176           ms/op
ClientPb.existUser                      sample  292056   3.285 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.085           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.625           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.804           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.934           ms/op
ClientPb.getUser                        sample  278817   3.441 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.019           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.314           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.676           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.892           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.812           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.032           ms/op
ClientPb.listUser                       sample  242818   3.953 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.294           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.988           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.534           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.817           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.000           ms/op
