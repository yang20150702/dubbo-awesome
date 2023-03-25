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
# Warmup Iteration   1: 2.123 ops/ms
# Warmup Iteration   2: 5.475 ops/ms
# Warmup Iteration   3: 8.754 ops/ms
Iteration   1: 9.440 ops/ms
Iteration   2: 9.533 ops/ms
Iteration   3: 9.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.534 ±(99.9%) 1.733 ops/ms [Average]
  (min, avg, max) = (9.440, 9.534, 9.630), stdev = 0.095
  CI (99.9%): [7.801, 11.268] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.851 ops/ms
# Warmup Iteration   2: 8.510 ops/ms
# Warmup Iteration   3: 9.420 ops/ms
Iteration   1: 9.333 ops/ms
Iteration   2: 9.899 ops/ms
Iteration   3: 9.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.685 ±(99.9%) 5.612 ops/ms [Average]
  (min, avg, max) = (9.333, 9.685, 9.899), stdev = 0.308
  CI (99.9%): [4.073, 15.297] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.827 ops/ms
# Warmup Iteration   2: 8.101 ops/ms
# Warmup Iteration   3: 9.047 ops/ms
Iteration   1: 9.333 ops/ms
Iteration   2: 9.290 ops/ms
Iteration   3: 9.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.380 ±(99.9%) 2.194 ops/ms [Average]
  (min, avg, max) = (9.290, 9.380, 9.517), stdev = 0.120
  CI (99.9%): [7.186, 11.574] (assumes normal distribution)


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
# Warmup Iteration   1: 2.850 ops/ms
# Warmup Iteration   2: 7.087 ops/ms
# Warmup Iteration   3: 8.098 ops/ms
Iteration   1: 7.981 ops/ms
Iteration   2: 8.007 ops/ms
Iteration   3: 8.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.057 ±(99.9%) 1.993 ops/ms [Average]
  (min, avg, max) = (7.981, 8.057, 8.182), stdev = 0.109
  CI (99.9%): [6.063, 10.050] (assumes normal distribution)


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
# Warmup Iteration   1: 8.443 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.007 ms/op
Iteration   1: 3.290 ±(99.9%) 0.004 ms/op
Iteration   2: 3.364 ±(99.9%) 0.012 ms/op
Iteration   3: 3.388 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.347 ±(99.9%) 0.930 ms/op [Average]
  (min, avg, max) = (3.290, 3.347, 3.388), stdev = 0.051
  CI (99.9%): [2.418, 4.277] (assumes normal distribution)


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
# Warmup Iteration   1: 7.223 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.003 ms/op
Iteration   1: 3.186 ±(99.9%) 0.005 ms/op
Iteration   2: 3.446 ±(99.9%) 0.005 ms/op
Iteration   3: 3.264 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.298 ±(99.9%) 2.436 ms/op [Average]
  (min, avg, max) = (3.186, 3.298, 3.446), stdev = 0.134
  CI (99.9%): [0.862, 5.734] (assumes normal distribution)


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
# Warmup Iteration   1: 9.914 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.003 ms/op
Iteration   1: 3.386 ±(99.9%) 0.004 ms/op
Iteration   2: 3.373 ±(99.9%) 0.005 ms/op
Iteration   3: 3.391 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.384 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (3.373, 3.384, 3.391), stdev = 0.009
  CI (99.9%): [3.215, 3.552] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.266 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.015 ms/op
Iteration   1: 3.876 ±(99.9%) 0.011 ms/op
Iteration   2: 3.830 ±(99.9%) 0.015 ms/op
Iteration   3: 3.897 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.868 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (3.830, 3.868, 3.897), stdev = 0.035
  CI (99.9%): [3.238, 4.498] (assumes normal distribution)


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
# Warmup Iteration   1: 9.392 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.876 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.009 ms/op
Iteration   1: 3.327 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.692 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  17.601 ms/op
                 createUser·p0.9999: 22.262 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   2: 3.325 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.706 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  18.503 ms/op
                 createUser·p0.9999: 24.818 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   3: 3.362 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  17.826 ms/op
                 createUser·p0.9999: 24.574 ms/op
                 createUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287711
  mean =      3.338 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8353 
    [ 2.500,  5.000) = 275091 
    [ 5.000,  7.500) = 3522 
    [ 7.500, 10.000) = 312 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     24.518 ms/op
     p(99.9990) =     25.403 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 8.119 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.009 ms/op
Iteration   1: 3.299 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.276 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  13.214 ms/op
                 existUser·p0.9999: 20.828 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   2: 3.275 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  12.419 ms/op
                 existUser·p0.9999: 23.331 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.264 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  10.061 ms/op
                 existUser·p0.9999: 26.775 ms/op
                 existUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293411
  mean =      3.267 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8677 
    [ 2.500,  5.000) = 279552 
    [ 5.000,  7.500) = 4208 
    [ 7.500, 10.000) = 531 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     12.386 ms/op
     p(99.9900) =     25.581 ms/op
     p(99.9990) =     27.044 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 9.132 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.009 ms/op
Iteration   1: 3.466 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  18.776 ms/op
                 getUser·p0.9999: 21.262 ms/op
                 getUser·p1.00:   21.922 ms/op

Iteration   2: 3.482 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.456 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  20.154 ms/op
                 getUser·p0.9999: 22.808 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.422 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  21.168 ms/op
                 getUser·p0.9999: 24.979 ms/op
                 getUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277690
  mean =      3.456 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12861 
    [ 2.500,  5.000) = 254783 
    [ 5.000,  7.500) = 8902 
    [ 7.500, 10.000) = 662 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 184 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     18.842 ms/op
     p(99.9900) =     24.132 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 10.817 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.435 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.014 ms/op
Iteration   1: 4.094 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  19.548 ms/op
                 listUser·p0.9999: 30.966 ms/op
                 listUser·p1.00:   32.014 ms/op

Iteration   2: 4.015 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.081 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 3.968 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.851 ms/op
                 listUser·p0.9999: 17.529 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238521
  mean =      4.025 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 229903 
    [ 5.000,  7.500) = 6331 
    [ 7.500, 10.000) = 1442 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     15.712 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     31.518 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.534 ± 1.733  ops/ms
ClientPb.existUser                       thrpt       3   9.685 ± 5.612  ops/ms
ClientPb.getUser                         thrpt       3   9.380 ± 2.194  ops/ms
ClientPb.listUser                        thrpt       3   8.057 ± 1.993  ops/ms
ClientPb.createUser                       avgt       3   3.347 ± 0.930   ms/op
ClientPb.existUser                        avgt       3   3.298 ± 2.436   ms/op
ClientPb.getUser                          avgt       3   3.384 ± 0.168   ms/op
ClientPb.listUser                         avgt       3   3.868 ± 0.630   ms/op
ClientPb.createUser                     sample  287711   3.338 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.509           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.826           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.518           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.690           ms/op
ClientPb.existUser                      sample  293411   3.267 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.983           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.386           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.581           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.558           ms/op
ClientPb.getUser                        sample  277690   3.456 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.120           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.604           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.842           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.132           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.051           ms/op
ClientPb.listUser                       sample  238521   4.025 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.462           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.406           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.712           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.410           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.014           ms/op
