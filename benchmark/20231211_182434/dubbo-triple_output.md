# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.890 ops/ms
# Warmup Iteration   2: 12.116 ops/ms
# Warmup Iteration   3: 12.365 ops/ms
Iteration   1: 12.588 ops/ms
Iteration   2: 12.605 ops/ms
Iteration   3: 12.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.632 ±(99.9%) 1.138 ops/ms [Average]
  (min, avg, max) = (12.588, 12.632, 12.704), stdev = 0.062
  CI (99.9%): [11.494, 13.771] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.959 ops/ms
# Warmup Iteration   2: 13.079 ops/ms
# Warmup Iteration   3: 13.112 ops/ms
Iteration   1: 12.995 ops/ms
Iteration   2: 13.003 ops/ms
Iteration   3: 13.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.060 ±(99.9%) 1.932 ops/ms [Average]
  (min, avg, max) = (12.995, 13.060, 13.183), stdev = 0.106
  CI (99.9%): [11.129, 14.992] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.924 ops/ms
# Warmup Iteration   2: 12.637 ops/ms
# Warmup Iteration   3: 12.644 ops/ms
Iteration   1: 12.770 ops/ms
Iteration   2: 12.725 ops/ms
Iteration   3: 12.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.769 ±(99.9%) 0.781 ops/ms [Average]
  (min, avg, max) = (12.725, 12.769, 12.811), stdev = 0.043
  CI (99.9%): [11.988, 13.549] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.693 ops/ms
# Warmup Iteration   2: 10.565 ops/ms
# Warmup Iteration   3: 10.627 ops/ms
Iteration   1: 10.701 ops/ms
Iteration   2: 10.712 ops/ms
Iteration   3: 10.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.709 ±(99.9%) 0.139 ops/ms [Average]
  (min, avg, max) = (10.701, 10.709, 10.716), stdev = 0.008
  CI (99.9%): [10.571, 10.848] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.974 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.004 ms/op
Iteration   1: 2.554 ±(99.9%) 0.003 ms/op
Iteration   2: 2.583 ±(99.9%) 0.004 ms/op
Iteration   3: 2.567 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.568 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.554, 2.568, 2.583), stdev = 0.015
  CI (99.9%): [2.297, 2.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.656 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.003 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.472 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.468 ±(99.9%) 0.089 ms/op [Average]
  (min, avg, max) = (2.462, 2.468, 2.472), stdev = 0.005
  CI (99.9%): [2.378, 2.557] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.811 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
Iteration   1: 2.522 ±(99.9%) 0.004 ms/op
Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.518 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (2.509, 2.518, 2.524), stdev = 0.008
  CI (99.9%): [2.369, 2.667] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.639 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 3.010 ±(99.9%) 0.004 ms/op
Iteration   2: 3.027 ±(99.9%) 0.005 ms/op
Iteration   3: 3.022 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.020 ±(99.9%) 0.156 ms/op [Average]
  (min, avg, max) = (3.010, 3.020, 3.027), stdev = 0.009
  CI (99.9%): [2.864, 3.175] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.250 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.667 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  11.010 ms/op
                 createUser·p0.9999: 14.293 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  9.903 ms/op
                 createUser·p0.9999: 12.456 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  8.442 ms/op
                 createUser·p0.9999: 10.924 ms/op
                 createUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381584
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 184329 
    [ 2.500,  3.750) = 193276 
    [ 3.750,  5.000) = 3088 
    [ 5.000,  6.250) = 412 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 129 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.777 ms/op
     p(99.9900) =     13.624 ms/op
     p(99.9990) =     14.568 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.622 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.411 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.410 ±(99.9%) 0.005 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  6.093 ms/op
                 existUser·p0.9999: 13.955 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   2: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  8.181 ms/op
                 existUser·p0.9999: 13.416 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   3: 2.403 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  7.791 ms/op
                 existUser·p0.9999: 12.681 ms/op
                 existUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395555
  mean =      2.424 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 198013 
    [ 2.500,  3.750) = 194485 
    [ 3.750,  5.000) = 2081 
    [ 5.000,  6.250) = 468 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      7.835 ms/op
     p(99.9900) =     13.384 ms/op
     p(99.9990) =     14.206 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.884 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.518 ms/op
                 getUser·p0.999:  7.226 ms/op
                 getUser·p0.9999: 14.914 ms/op
                 getUser·p1.00:   15.794 ms/op

Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  10.971 ms/op
                 getUser·p0.9999: 17.651 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 15.421 ms/op
                 getUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382779
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 189492 
    [ 2.500,  3.750) = 188754 
    [ 3.750,  5.000) = 3435 
    [ 5.000,  6.250) = 631 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.605 ms/op
     p(99.9900) =     15.526 ms/op
     p(99.9990) =     18.203 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.697 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
Iteration   1: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  8.815 ms/op
                 listUser·p0.9999: 10.212 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   2: 2.964 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 11.243 ms/op
                 listUser·p1.00:   12.173 ms/op

Iteration   3: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.745 ms/op
                 listUser·p0.9999: 11.833 ms/op
                 listUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322546
  mean =      2.974 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 100806 
    [ 2.500,  3.750) = 184847 
    [ 3.750,  5.000) = 30143 
    [ 5.000,  6.250) = 5427 
    [ 6.250,  7.500) = 548 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 221 
    [10.000, 11.250) = 158 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     11.460 ms/op
     p(99.9990) =     12.166 ms/op
     p(99.9999) =     12.435 ms/op
    p(100.0000) =     12.435 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.632 ± 1.138  ops/ms
ClientPb.existUser                       thrpt       3  13.060 ± 1.932  ops/ms
ClientPb.getUser                         thrpt       3  12.769 ± 0.781  ops/ms
ClientPb.listUser                        thrpt       3  10.709 ± 0.139  ops/ms
ClientPb.createUser                       avgt       3   2.568 ± 0.271   ms/op
ClientPb.existUser                        avgt       3   2.468 ± 0.089   ms/op
ClientPb.getUser                          avgt       3   2.518 ± 0.149   ms/op
ClientPb.listUser                         avgt       3   3.020 ± 0.156   ms/op
ClientPb.createUser                     sample  381584   2.514 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.842           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.777           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.624           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.664           ms/op
ClientPb.existUser                      sample  395555   2.424 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.555           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.835           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.384           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.287           ms/op
ClientPb.getUser                        sample  382779   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.921           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.605           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.526           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.448           ms/op
ClientPb.listUser                       sample  322546   2.974 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.809           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.460           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.435           ms/op
