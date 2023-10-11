# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.071 ops/ms
# Warmup Iteration   2: 5.613 ops/ms
# Warmup Iteration   3: 8.226 ops/ms
Iteration   1: 8.706 ops/ms
Iteration   2: 8.978 ops/ms
Iteration   3: 8.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.819 ±(99.9%) 2.591 ops/ms [Average]
  (min, avg, max) = (8.706, 8.819, 8.978), stdev = 0.142
  CI (99.9%): [6.227, 11.410] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.959 ops/ms
# Warmup Iteration   2: 8.478 ops/ms
# Warmup Iteration   3: 9.060 ops/ms
Iteration   1: 9.419 ops/ms
Iteration   2: 8.910 ops/ms
Iteration   3: 9.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.189 ±(99.9%) 4.709 ops/ms [Average]
  (min, avg, max) = (8.910, 9.189, 9.419), stdev = 0.258
  CI (99.9%): [4.480, 13.898] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.499 ops/ms
# Warmup Iteration   2: 8.276 ops/ms
# Warmup Iteration   3: 8.773 ops/ms
Iteration   1: 8.794 ops/ms
Iteration   2: 9.085 ops/ms
Iteration   3: 8.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.940 ±(99.9%) 2.659 ops/ms [Average]
  (min, avg, max) = (8.794, 8.940, 9.085), stdev = 0.146
  CI (99.9%): [6.281, 11.599] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.503 ops/ms
# Warmup Iteration   2: 6.308 ops/ms
# Warmup Iteration   3: 7.467 ops/ms
Iteration   1: 7.427 ops/ms
Iteration   2: 7.691 ops/ms
Iteration   3: 7.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.616 ±(99.9%) 3.014 ops/ms [Average]
  (min, avg, max) = (7.427, 7.616, 7.730), stdev = 0.165
  CI (99.9%): [4.602, 10.630] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 9.387 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.005 ms/op
Iteration   1: 3.479 ±(99.9%) 0.003 ms/op
Iteration   2: 3.472 ±(99.9%) 0.007 ms/op
Iteration   3: 3.498 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.483 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (3.472, 3.483, 3.498), stdev = 0.014
  CI (99.9%): [3.234, 3.732] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.758 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.005 ms/op
Iteration   1: 3.418 ±(99.9%) 0.006 ms/op
Iteration   2: 3.349 ±(99.9%) 0.002 ms/op
Iteration   3: 3.373 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.380 ±(99.9%) 0.637 ms/op [Average]
  (min, avg, max) = (3.349, 3.380, 3.418), stdev = 0.035
  CI (99.9%): [2.743, 4.017] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.615 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.005 ms/op
Iteration   1: 3.561 ±(99.9%) 0.002 ms/op
Iteration   2: 3.657 ±(99.9%) 0.003 ms/op
Iteration   3: 3.550 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.590 ±(99.9%) 1.076 ms/op [Average]
  (min, avg, max) = (3.550, 3.590, 3.657), stdev = 0.059
  CI (99.9%): [2.514, 4.665] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.170 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.642 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.345 ±(99.9%) 0.007 ms/op
Iteration   1: 4.169 ±(99.9%) 0.006 ms/op
Iteration   2: 4.160 ±(99.9%) 0.009 ms/op
Iteration   3: 4.292 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.207 ±(99.9%) 1.347 ms/op [Average]
  (min, avg, max) = (4.160, 4.207, 4.292), stdev = 0.074
  CI (99.9%): [2.860, 5.554] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.633 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.015 ms/op
Iteration   1: 3.687 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   7.342 ms/op
                 createUser·p0.999:  22.195 ms/op
                 createUser·p0.9999: 25.416 ms/op
                 createUser·p1.00:   26.771 ms/op

Iteration   2: 3.581 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  24.073 ms/op
                 createUser·p0.9999: 26.315 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   3: 3.525 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.698 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  24.089 ms/op
                 createUser·p0.9999: 28.410 ms/op
                 createUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 266983
  mean =      3.596 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3210 
    [ 2.500,  5.000) = 253931 
    [ 5.000,  7.500) = 7983 
    [ 7.500, 10.000) = 1105 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 115 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     23.036 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     29.479 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.346 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.010 ms/op
Iteration   1: 3.450 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.716 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   7.340 ms/op
                 existUser·p0.999:  21.080 ms/op
                 existUser·p0.9999: 25.002 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   2: 3.402 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  22.737 ms/op
                 existUser·p0.9999: 25.821 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   3: 3.404 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.583 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   7.160 ms/op
                 existUser·p0.999:  12.599 ms/op
                 existUser·p0.9999: 31.923 ms/op
                 existUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280748
  mean =      3.419 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8996 
    [ 2.500,  5.000) = 261981 
    [ 5.000,  7.500) = 7649 
    [ 7.500, 10.000) = 1300 
    [10.000, 12.500) = 397 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     16.765 ms/op
     p(99.9900) =     31.057 ms/op
     p(99.9990) =     32.418 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.063 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.015 ms/op
Iteration   1: 3.655 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  20.758 ms/op
                 getUser·p0.9999: 24.650 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   2: 3.724 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.876 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   5.472 ms/op
                 getUser·p0.99:   8.012 ms/op
                 getUser·p0.999:  15.289 ms/op
                 getUser·p0.9999: 24.295 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   3: 3.598 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  24.396 ms/op
                 getUser·p0.9999: 27.201 ms/op
                 getUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 262196
  mean =      3.658 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2077 
    [ 2.500,  5.000) = 248591 
    [ 5.000,  7.500) = 8310 
    [ 7.500, 10.000) = 2549 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 74 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     20.637 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     27.759 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.034 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.563 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.312 ±(99.9%) 0.014 ms/op
Iteration   1: 4.253 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   4.108 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  21.015 ms/op
                 listUser·p0.9999: 28.258 ms/op
                 listUser·p1.00:   28.770 ms/op

Iteration   2: 4.301 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  18.045 ms/op
                 listUser·p0.9999: 21.458 ms/op
                 listUser·p1.00:   29.426 ms/op

Iteration   3: 4.325 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   4.166 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   8.456 ms/op
                 listUser·p0.999:  16.433 ms/op
                 listUser·p0.9999: 25.238 ms/op
                 listUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 223429
  mean =      4.293 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 211252 
    [ 5.000,  7.500) = 8342 
    [ 7.500, 10.000) = 2523 
    [10.000, 12.500) = 436 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 367 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      4.137 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     18.762 ms/op
     p(99.9900) =     25.362 ms/op
     p(99.9990) =     29.272 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.819 ± 2.591  ops/ms
ClientPb.existUser                       thrpt       3   9.189 ± 4.709  ops/ms
ClientPb.getUser                         thrpt       3   8.940 ± 2.659  ops/ms
ClientPb.listUser                        thrpt       3   7.616 ± 3.014  ops/ms
ClientPb.createUser                       avgt       3   3.483 ± 0.249   ms/op
ClientPb.existUser                        avgt       3   3.380 ± 0.637   ms/op
ClientPb.getUser                          avgt       3   3.590 ± 1.076   ms/op
ClientPb.listUser                         avgt       3   4.207 ± 1.347   ms/op
ClientPb.createUser                     sample  266983   3.596 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.251           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.149           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.538           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.045           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.036           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.853           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.852           ms/op
ClientPb.existUser                      sample  280748   3.419 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.270           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.102           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.765           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.057           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.899           ms/op
ClientPb.getUser                        sample  262196   3.658 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.231           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.465           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.719           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.676           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.637           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.214           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.639           ms/op
ClientPb.listUser                       sample  223429   4.293 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.141           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.137           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.095           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.762           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.362           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.507           ms/op
