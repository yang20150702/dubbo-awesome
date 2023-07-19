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
# Warmup Iteration   1: 2.053 ops/ms
# Warmup Iteration   2: 5.285 ops/ms
# Warmup Iteration   3: 8.374 ops/ms
Iteration   1: 8.714 ops/ms
Iteration   2: 9.189 ops/ms
Iteration   3: 9.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.163 ±(99.9%) 7.974 ops/ms [Average]
  (min, avg, max) = (8.714, 9.163, 9.587), stdev = 0.437
  CI (99.9%): [1.189, 17.137] (assumes normal distribution)


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
# Warmup Iteration   1: 2.890 ops/ms
# Warmup Iteration   2: 8.709 ops/ms
# Warmup Iteration   3: 9.140 ops/ms
Iteration   1: 9.568 ops/ms
Iteration   2: 10.014 ops/ms
Iteration   3: 9.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.850 ±(99.9%) 4.471 ops/ms [Average]
  (min, avg, max) = (9.568, 9.850, 10.014), stdev = 0.245
  CI (99.9%): [5.379, 14.321] (assumes normal distribution)


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
# Warmup Iteration   1: 2.734 ops/ms
# Warmup Iteration   2: 8.451 ops/ms
# Warmup Iteration   3: 9.039 ops/ms
Iteration   1: 9.316 ops/ms
Iteration   2: 8.914 ops/ms
Iteration   3: 8.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.045 ±(99.9%) 4.283 ops/ms [Average]
  (min, avg, max) = (8.906, 9.045, 9.316), stdev = 0.235
  CI (99.9%): [4.763, 13.328] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.713 ops/ms
# Warmup Iteration   2: 7.238 ops/ms
# Warmup Iteration   3: 7.712 ops/ms
Iteration   1: 8.084 ops/ms
Iteration   2: 7.858 ops/ms
Iteration   3: 7.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.963 ±(99.9%) 2.074 ops/ms [Average]
  (min, avg, max) = (7.858, 7.963, 8.084), stdev = 0.114
  CI (99.9%): [5.889, 10.038] (assumes normal distribution)


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
# Warmup Iteration   1: 9.504 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.004 ms/op
Iteration   1: 3.435 ±(99.9%) 0.007 ms/op
Iteration   2: 3.437 ±(99.9%) 0.009 ms/op
Iteration   3: 3.456 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.443 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (3.435, 3.443, 3.456), stdev = 0.012
  CI (99.9%): [3.229, 3.656] (assumes normal distribution)


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
# Warmup Iteration   1: 9.649 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.333 ±(99.9%) 0.003 ms/op
Iteration   1: 3.377 ±(99.9%) 0.009 ms/op
Iteration   2: 3.402 ±(99.9%) 0.005 ms/op
Iteration   3: 3.353 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.377 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (3.353, 3.377, 3.402), stdev = 0.024
  CI (99.9%): [2.936, 3.819] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.715 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.006 ms/op
Iteration   1: 3.410 ±(99.9%) 0.010 ms/op
Iteration   2: 3.565 ±(99.9%) 0.006 ms/op
Iteration   3: 3.400 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.459 ±(99.9%) 1.684 ms/op [Average]
  (min, avg, max) = (3.400, 3.459, 3.565), stdev = 0.092
  CI (99.9%): [1.774, 5.143] (assumes normal distribution)


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
# Warmup Iteration   1: 10.855 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.695 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.008 ms/op
Iteration   1: 4.005 ±(99.9%) 0.010 ms/op
Iteration   2: 4.051 ±(99.9%) 0.013 ms/op
Iteration   3: 3.980 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.012 ±(99.9%) 0.651 ms/op [Average]
  (min, avg, max) = (3.980, 4.012, 4.051), stdev = 0.036
  CI (99.9%): [3.361, 4.663] (assumes normal distribution)


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
# Warmup Iteration   1: 10.285 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.010 ms/op
Iteration   1: 3.756 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.765 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   6.210 ms/op
                 createUser·p0.99:   7.586 ms/op
                 createUser·p0.999:  11.272 ms/op
                 createUser·p0.9999: 30.114 ms/op
                 createUser·p1.00:   30.474 ms/op

Iteration   2: 3.454 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.761 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  23.032 ms/op
                 createUser·p0.9999: 25.755 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   3: 3.574 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.819 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  19.276 ms/op
                 createUser·p0.9999: 28.084 ms/op
                 createUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267321
  mean =      3.591 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2954 
    [ 2.500,  5.000) = 254006 
    [ 5.000,  7.500) = 8574 
    [ 7.500, 10.000) = 1257 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.761 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     27.534 ms/op
     p(99.9990) =     30.266 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 9.723 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.008 ms/op
Iteration   1: 3.291 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  17.007 ms/op
                 existUser·p0.9999: 22.160 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   2: 3.302 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  11.276 ms/op
                 existUser·p0.9999: 26.791 ms/op
                 existUser·p1.00:   28.967 ms/op

Iteration   3: 3.494 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  9.503 ms/op
                 existUser·p0.9999: 25.292 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285698
  mean =      3.360 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14301 
    [ 2.500,  5.000) = 265671 
    [ 5.000,  7.500) = 4891 
    [ 7.500, 10.000) = 449 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     15.788 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     27.483 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 10.951 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.013 ms/op
Iteration   1: 3.567 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.084 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  21.148 ms/op
                 getUser·p0.9999: 29.365 ms/op
                 getUser·p1.00:   30.867 ms/op

Iteration   2: 3.516 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.487 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  22.249 ms/op
                 getUser·p0.9999: 25.163 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   3: 3.535 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  20.580 ms/op
                 getUser·p0.9999: 27.391 ms/op
                 getUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271037
  mean =      3.539 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4390 
    [ 2.500,  5.000) = 256309 
    [ 5.000,  7.500) = 8976 
    [ 7.500, 10.000) = 933 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     21.069 ms/op
     p(99.9900) =     27.915 ms/op
     p(99.9990) =     30.844 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 10.812 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 5.013 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.392 ±(99.9%) 0.017 ms/op
Iteration   1: 4.153 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.611 ms/op
                 listUser·p0.999:  20.775 ms/op
                 listUser·p0.9999: 26.536 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   2: 4.124 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.995 ms/op
                 listUser·p0.999:  15.252 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 4.022 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 17.891 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234043
  mean =      4.099 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 225213 
    [ 5.000,  7.500) = 6175 
    [ 7.500, 10.000) = 1677 
    [10.000, 12.500) = 415 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.630 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.700 ms/op
     p(99.9000) =     15.743 ms/op
     p(99.9900) =     23.449 ms/op
     p(99.9990) =     27.053 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.163 ± 7.974  ops/ms
ClientPb.existUser                       thrpt       3   9.850 ± 4.471  ops/ms
ClientPb.getUser                         thrpt       3   9.045 ± 4.283  ops/ms
ClientPb.listUser                        thrpt       3   7.963 ± 2.074  ops/ms
ClientPb.createUser                       avgt       3   3.443 ± 0.214   ms/op
ClientPb.existUser                        avgt       3   3.377 ± 0.442   ms/op
ClientPb.getUser                          avgt       3   3.459 ± 1.684   ms/op
ClientPb.listUser                         avgt       3   4.012 ± 0.651   ms/op
ClientPb.createUser                     sample  267321   3.591 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.761           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.908           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.534           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.474           ms/op
ClientPb.existUser                      sample  285698   3.360 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.065           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.788           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.083           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.967           ms/op
ClientPb.getUser                        sample  271037   3.539 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.098           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.554           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.069           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.915           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.867           ms/op
ClientPb.listUser                       sample  234043   4.099 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.630           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.700           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.743           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.449           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.197           ms/op
