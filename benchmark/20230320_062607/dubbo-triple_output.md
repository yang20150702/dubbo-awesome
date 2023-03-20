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
# Warmup Iteration   1: 2.629 ops/ms
# Warmup Iteration   2: 6.519 ops/ms
# Warmup Iteration   3: 9.418 ops/ms
Iteration   1: 9.908 ops/ms
Iteration   2: 9.768 ops/ms
Iteration   3: 10.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.970 ±(99.9%) 4.355 ops/ms [Average]
  (min, avg, max) = (9.768, 9.970, 10.233), stdev = 0.239
  CI (99.9%): [5.614, 14.325] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ops/ms
# Warmup Iteration   2: 9.599 ops/ms
# Warmup Iteration   3: 10.462 ops/ms
Iteration   1: 10.497 ops/ms
Iteration   2: 10.149 ops/ms
Iteration   3: 10.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.376 ±(99.9%) 3.595 ops/ms [Average]
  (min, avg, max) = (10.149, 10.376, 10.497), stdev = 0.197
  CI (99.9%): [6.781, 13.971] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.861 ops/ms
# Warmup Iteration   2: 9.224 ops/ms
# Warmup Iteration   3: 10.085 ops/ms
Iteration   1: 9.661 ops/ms
Iteration   2: 9.998 ops/ms
Iteration   3: 10.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.015 ±(99.9%) 6.637 ops/ms [Average]
  (min, avg, max) = (9.661, 10.015, 10.388), stdev = 0.364
  CI (99.9%): [3.378, 16.652] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.331 ops/ms
# Warmup Iteration   2: 7.702 ops/ms
# Warmup Iteration   3: 8.726 ops/ms
Iteration   1: 8.890 ops/ms
Iteration   2: 8.649 ops/ms
Iteration   3: 8.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.799 ±(99.9%) 2.391 ops/ms [Average]
  (min, avg, max) = (8.649, 8.799, 8.890), stdev = 0.131
  CI (99.9%): [6.409, 11.190] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.458 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.386 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.006 ms/op
Iteration   1: 3.266 ±(99.9%) 0.006 ms/op
Iteration   2: 3.024 ±(99.9%) 0.009 ms/op
Iteration   3: 3.114 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.135 ±(99.9%) 2.235 ms/op [Average]
  (min, avg, max) = (3.024, 3.135, 3.266), stdev = 0.123
  CI (99.9%): [0.899, 5.370] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.204 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.006 ms/op
Iteration   1: 3.114 ±(99.9%) 0.009 ms/op
Iteration   2: 3.006 ±(99.9%) 0.005 ms/op
Iteration   3: 2.988 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.036 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (2.988, 3.036, 3.114), stdev = 0.068
  CI (99.9%): [1.797, 4.275] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 7.692 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.387 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.003 ms/op
Iteration   1: 3.267 ±(99.9%) 0.003 ms/op
Iteration   2: 3.151 ±(99.9%) 0.003 ms/op
Iteration   3: 3.273 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.230 ±(99.9%) 1.250 ms/op [Average]
  (min, avg, max) = (3.151, 3.230, 3.273), stdev = 0.069
  CI (99.9%): [1.981, 4.480] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 8.803 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.005 ms/op
Iteration   1: 3.702 ±(99.9%) 0.005 ms/op
Iteration   2: 3.694 ±(99.9%) 0.009 ms/op
Iteration   3: 3.671 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.689 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (3.671, 3.689, 3.702), stdev = 0.016
  CI (99.9%): [3.394, 3.984] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.328 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.008 ms/op
Iteration   1: 3.060 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.334 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  8.478 ms/op
                 createUser·p0.9999: 21.579 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.553 ms/op
                 createUser·p0.999:  10.879 ms/op
                 createUser·p0.9999: 22.216 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   3: 3.147 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  16.073 ms/op
                 createUser·p0.9999: 18.574 ms/op
                 createUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306377
  mean =      3.132 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17830 
    [ 2.500,  5.000) = 284470 
    [ 5.000,  7.500) = 3367 
    [ 7.500, 10.000) = 326 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     15.509 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     23.017 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 6.811 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
Iteration   1: 3.130 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  10.533 ms/op
                 existUser·p0.9999: 22.994 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   2: 3.228 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.464 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  7.678 ms/op
                 existUser·p0.9999: 21.985 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   3: 3.063 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.212 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  13.033 ms/op
                 existUser·p0.9999: 44.469 ms/op
                 existUser·p1.00:   45.875 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306000
  mean =      3.139 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 300659 
    [ 5.000, 10.000) = 4953 
    [10.000, 15.000) = 131 
    [15.000, 20.000) = 102 
    [20.000, 25.000) = 121 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     12.337 ms/op
     p(99.9900) =     43.739 ms/op
     p(99.9990) =     45.798 ms/op
     p(99.9999) =     45.875 ms/op
    p(100.0000) =     45.875 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 7.674 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.356 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.008 ms/op
Iteration   1: 3.136 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.531 ms/op
                 getUser·p0.99:   5.526 ms/op
                 getUser·p0.999:  17.890 ms/op
                 getUser·p0.9999: 20.047 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   2: 3.156 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  11.653 ms/op
                 getUser·p0.9999: 31.420 ms/op
                 getUser·p1.00:   32.113 ms/op

Iteration   3: 3.277 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  12.635 ms/op
                 getUser·p0.9999: 17.318 ms/op
                 getUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300900
  mean =      3.188 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10188 
    [ 2.500,  5.000) = 282504 
    [ 5.000,  7.500) = 7088 
    [ 7.500, 10.000) = 646 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     30.338 ms/op
     p(99.9990) =     31.719 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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
# Warmup Iteration   1: 9.311 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.012 ms/op
Iteration   1: 3.728 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.003 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 19.702 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   2: 3.678 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 15.078 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   3: 3.802 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  14.189 ms/op
                 listUser·p0.9999: 18.271 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256739
  mean =      3.735 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 248220 
    [ 5.000,  7.500) = 6527 
    [ 7.500, 10.000) = 1186 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.003 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     20.021 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.970 ± 4.355  ops/ms
ClientPb.existUser                       thrpt       3  10.376 ± 3.595  ops/ms
ClientPb.getUser                         thrpt       3  10.015 ± 6.637  ops/ms
ClientPb.listUser                        thrpt       3   8.799 ± 2.391  ops/ms
ClientPb.createUser                       avgt       3   3.135 ± 2.235   ms/op
ClientPb.existUser                        avgt       3   3.036 ± 1.239   ms/op
ClientPb.getUser                          avgt       3   3.230 ± 1.250   ms/op
ClientPb.listUser                         avgt       3   3.689 ± 0.295   ms/op
ClientPb.createUser                     sample  306377   3.132 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.934           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.276           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.509           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.889           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.200           ms/op
ClientPb.existUser                      sample  306000   3.139 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.212           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.026           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.337           ms/op
ClientPb.existUser:existUser·p0.9999    sample          43.739           ms/op
ClientPb.existUser:existUser·p1.00      sample          45.875           ms/op
ClientPb.getUser                        sample  300900   3.188 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.141           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.494           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.119           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.795           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.338           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.113           ms/op
ClientPb.listUser                       sample  256739   3.735 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.003           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.189           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.940           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.775           ms/op
