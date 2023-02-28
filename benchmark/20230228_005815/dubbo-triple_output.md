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
# Warmup Iteration   1: 2.144 ops/ms
# Warmup Iteration   2: 4.958 ops/ms
# Warmup Iteration   3: 8.567 ops/ms
Iteration   1: 9.103 ops/ms
Iteration   2: 9.551 ops/ms
Iteration   3: 9.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.351 ±(99.9%) 4.154 ops/ms [Average]
  (min, avg, max) = (9.103, 9.351, 9.551), stdev = 0.228
  CI (99.9%): [5.197, 13.505] (assumes normal distribution)


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
# Warmup Iteration   1: 2.955 ops/ms
# Warmup Iteration   2: 9.069 ops/ms
# Warmup Iteration   3: 9.627 ops/ms
Iteration   1: 9.672 ops/ms
Iteration   2: 9.600 ops/ms
Iteration   3: 9.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.657 ±(99.9%) 0.922 ops/ms [Average]
  (min, avg, max) = (9.600, 9.657, 9.698), stdev = 0.051
  CI (99.9%): [8.735, 10.578] (assumes normal distribution)


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
# Warmup Iteration   1: 2.774 ops/ms
# Warmup Iteration   2: 8.670 ops/ms
# Warmup Iteration   3: 9.299 ops/ms
Iteration   1: 9.448 ops/ms
Iteration   2: 9.537 ops/ms
Iteration   3: 9.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.495 ±(99.9%) 0.816 ops/ms [Average]
  (min, avg, max) = (9.448, 9.495, 9.537), stdev = 0.045
  CI (99.9%): [8.679, 10.310] (assumes normal distribution)


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
# Warmup Iteration   1: 2.434 ops/ms
# Warmup Iteration   2: 7.119 ops/ms
# Warmup Iteration   3: 7.757 ops/ms
Iteration   1: 8.185 ops/ms
Iteration   2: 8.384 ops/ms
Iteration   3: 8.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.277 ±(99.9%) 1.829 ops/ms [Average]
  (min, avg, max) = (8.185, 8.277, 8.384), stdev = 0.100
  CI (99.9%): [6.447, 10.106] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.777 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.004 ms/op
Iteration   1: 3.374 ±(99.9%) 0.006 ms/op
Iteration   2: 3.317 ±(99.9%) 0.008 ms/op
Iteration   3: 3.391 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.361 ±(99.9%) 0.707 ms/op [Average]
  (min, avg, max) = (3.317, 3.361, 3.391), stdev = 0.039
  CI (99.9%): [2.653, 4.068] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.240 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.006 ms/op
Iteration   1: 3.214 ±(99.9%) 0.008 ms/op
Iteration   2: 3.238 ±(99.9%) 0.008 ms/op
Iteration   3: 3.216 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.223 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (3.214, 3.223, 3.238), stdev = 0.013
  CI (99.9%): [2.986, 3.459] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.334 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.004 ms/op
Iteration   1: 3.376 ±(99.9%) 0.006 ms/op
Iteration   2: 3.480 ±(99.9%) 0.004 ms/op
Iteration   3: 3.333 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.397 ±(99.9%) 1.378 ms/op [Average]
  (min, avg, max) = (3.333, 3.397, 3.480), stdev = 0.076
  CI (99.9%): [2.018, 4.775] (assumes normal distribution)


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
# Warmup Iteration   1: 9.911 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.011 ms/op
Iteration   1: 3.934 ±(99.9%) 0.007 ms/op
Iteration   2: 3.821 ±(99.9%) 0.010 ms/op
Iteration   3: 3.829 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.861 ±(99.9%) 1.147 ms/op [Average]
  (min, avg, max) = (3.821, 3.861, 3.934), stdev = 0.063
  CI (99.9%): [2.714, 5.009] (assumes normal distribution)


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
# Warmup Iteration   1: 10.846 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.696 ±(99.9%) 0.014 ms/op
Iteration   1: 3.456 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  20.627 ms/op
                 createUser·p0.9999: 25.125 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 3.350 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.796 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  21.578 ms/op
                 createUser·p0.9999: 24.963 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   3: 3.365 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.943 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 28.033 ms/op
                 createUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282958
  mean =      3.390 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6258 
    [ 2.500,  5.000) = 270668 
    [ 5.000,  7.500) = 4917 
    [ 7.500, 10.000) = 590 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.671 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     18.618 ms/op
     p(99.9900) =     26.756 ms/op
     p(99.9990) =     30.453 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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
# Warmup Iteration   1: 9.842 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
Iteration   1: 3.430 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.489 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  19.940 ms/op
                 existUser·p0.9999: 23.236 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   2: 3.325 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  17.855 ms/op
                 existUser·p0.9999: 25.494 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   3: 3.351 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  14.139 ms/op
                 existUser·p0.9999: 26.437 ms/op
                 existUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284990
  mean =      3.368 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12949 
    [ 2.500,  5.000) = 265147 
    [ 5.000,  7.500) = 5877 
    [ 7.500, 10.000) = 566 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     26.809 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 9.297 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.010 ms/op
Iteration   1: 3.471 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  12.848 ms/op
                 getUser·p0.9999: 25.669 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   2: 3.452 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.626 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   6.799 ms/op
                 getUser·p0.999:  22.983 ms/op
                 getUser·p0.9999: 25.509 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 3.447 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  20.618 ms/op
                 getUser·p0.9999: 26.777 ms/op
                 getUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277537
  mean =      3.457 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4043 
    [ 2.500,  5.000) = 264890 
    [ 5.000,  7.500) = 6920 
    [ 7.500, 10.000) = 1143 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.824 ms/op
     p(99.9900) =     25.903 ms/op
     p(99.9990) =     29.204 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 10.556 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.318 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.012 ms/op
Iteration   1: 3.935 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.446 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.470 ms/op
                 listUser·p0.999:  19.487 ms/op
                 listUser·p0.9999: 25.537 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   2: 4.072 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  16.728 ms/op
                 listUser·p0.9999: 19.857 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 3.960 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  15.480 ms/op
                 listUser·p0.9999: 20.314 ms/op
                 listUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240667
  mean =      3.988 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 231336 
    [ 5.000,  7.500) = 7134 
    [ 7.500, 10.000) = 1403 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     23.291 ms/op
     p(99.9990) =     25.880 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.351 ± 4.154  ops/ms
ClientPb.existUser                       thrpt       3   9.657 ± 0.922  ops/ms
ClientPb.getUser                         thrpt       3   9.495 ± 0.816  ops/ms
ClientPb.listUser                        thrpt       3   8.277 ± 1.829  ops/ms
ClientPb.createUser                       avgt       3   3.361 ± 0.707   ms/op
ClientPb.existUser                        avgt       3   3.223 ± 0.237   ms/op
ClientPb.getUser                          avgt       3   3.397 ± 1.378   ms/op
ClientPb.listUser                         avgt       3   3.861 ± 1.147   ms/op
ClientPb.createUser                     sample  282958   3.390 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.671           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.841           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.618           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.756           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.736           ms/op
ClientPb.existUser                      sample  284990   3.368 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.067           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.189           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.559           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.870           ms/op
ClientPb.getUser                        sample  277537   3.457 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.272           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.791           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.824           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.903           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753           ms/op
ClientPb.listUser                       sample  240667   3.988 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.284           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.340           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.203           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.291           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.919           ms/op
