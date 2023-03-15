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
# Warmup Iteration   1: 0.985 ops/ms
# Warmup Iteration   2: 2.190 ops/ms
# Warmup Iteration   3: 4.755 ops/ms
Iteration   1: 5.697 ops/ms
Iteration   2: 6.044 ops/ms
Iteration   3: 5.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.911 ±(99.9%) 3.415 ops/ms [Average]
  (min, avg, max) = (5.697, 5.911, 6.044), stdev = 0.187
  CI (99.9%): [2.497, 9.326] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.652 ops/ms
# Warmup Iteration   2: 4.479 ops/ms
# Warmup Iteration   3: 5.799 ops/ms
Iteration   1: 6.180 ops/ms
Iteration   2: 6.230 ops/ms
Iteration   3: 5.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.127 ±(99.9%) 2.510 ops/ms [Average]
  (min, avg, max) = (5.971, 6.127, 6.230), stdev = 0.138
  CI (99.9%): [3.617, 8.637] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.705 ops/ms
# Warmup Iteration   2: 4.546 ops/ms
# Warmup Iteration   3: 5.862 ops/ms
Iteration   1: 5.742 ops/ms
Iteration   2: 5.866 ops/ms
Iteration   3: 6.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.929 ±(99.9%) 4.107 ops/ms [Average]
  (min, avg, max) = (5.742, 5.929, 6.179), stdev = 0.225
  CI (99.9%): [1.822, 10.036] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.405 ops/ms
# Warmup Iteration   2: 3.915 ops/ms
# Warmup Iteration   3: 4.952 ops/ms
Iteration   1: 4.879 ops/ms
Iteration   2: 4.886 ops/ms
Iteration   3: 4.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.820 ±(99.9%) 1.965 ops/ms [Average]
  (min, avg, max) = (4.696, 4.820, 4.886), stdev = 0.108
  CI (99.9%): [2.856, 6.785] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.871 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 7.501 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.746 ±(99.9%) 0.013 ms/op
Iteration   1: 5.751 ±(99.9%) 0.012 ms/op
Iteration   2: 5.394 ±(99.9%) 0.023 ms/op
Iteration   3: 5.394 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.513 ±(99.9%) 3.760 ms/op [Average]
  (min, avg, max) = (5.394, 5.513, 5.751), stdev = 0.206
  CI (99.9%): [1.753, 9.273] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.808 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.737 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.403 ±(99.9%) 0.007 ms/op
Iteration   1: 5.246 ±(99.9%) 0.010 ms/op
Iteration   2: 4.980 ±(99.9%) 0.013 ms/op
Iteration   3: 5.235 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.154 ±(99.9%) 2.751 ms/op [Average]
  (min, avg, max) = (4.980, 5.154, 5.246), stdev = 0.151
  CI (99.9%): [2.403, 7.905] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.729 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.297 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.693 ±(99.9%) 0.011 ms/op
Iteration   1: 5.660 ±(99.9%) 0.008 ms/op
Iteration   2: 5.547 ±(99.9%) 0.007 ms/op
Iteration   3: 5.469 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.559 ±(99.9%) 1.748 ms/op [Average]
  (min, avg, max) = (5.469, 5.559, 5.660), stdev = 0.096
  CI (99.9%): [3.811, 7.307] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.740 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 9.174 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.553 ±(99.9%) 0.013 ms/op
Iteration   1: 6.335 ±(99.9%) 0.013 ms/op
Iteration   2: 6.138 ±(99.9%) 0.016 ms/op
Iteration   3: 6.231 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.235 ±(99.9%) 1.803 ms/op [Average]
  (min, avg, max) = (6.138, 6.235, 6.335), stdev = 0.099
  CI (99.9%): [4.432, 8.038] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.346 ±(99.9%) 0.281 ms/op
# Warmup Iteration   2: 7.045 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.913 ±(99.9%) 0.025 ms/op
Iteration   1: 5.628 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.478 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   7.422 ms/op
                 createUser·p0.95:   8.405 ms/op
                 createUser·p0.99:   12.042 ms/op
                 createUser·p0.999:  24.745 ms/op
                 createUser·p0.9999: 32.789 ms/op
                 createUser·p1.00:   34.669 ms/op

Iteration   2: 5.524 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.347 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   6.783 ms/op
                 createUser·p0.95:   7.578 ms/op
                 createUser·p0.99:   10.863 ms/op
                 createUser·p0.999:  25.934 ms/op
                 createUser·p0.9999: 30.308 ms/op
                 createUser·p1.00:   31.425 ms/op

Iteration   3: 5.652 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.163 ms/op
                 createUser·p0.50:   5.366 ms/op
                 createUser·p0.90:   7.201 ms/op
                 createUser·p0.95:   8.069 ms/op
                 createUser·p0.99:   10.830 ms/op
                 createUser·p0.999:  17.302 ms/op
                 createUser·p0.9999: 31.305 ms/op
                 createUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171241
  mean =      5.600 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 67479 
    [ 5.000,  7.500) = 90738 
    [ 7.500, 10.000) = 10193 
    [10.000, 12.500) = 1730 
    [12.500, 15.000) = 597 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      7.111 ms/op
     p(95.0000) =      8.036 ms/op
     p(99.0000) =     11.256 ms/op
     p(99.9000) =     23.290 ms/op
     p(99.9900) =     32.240 ms/op
     p(99.9990) =     34.295 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 18.517 ±(99.9%) 0.315 ms/op
# Warmup Iteration   2: 6.698 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.508 ±(99.9%) 0.021 ms/op
Iteration   1: 5.633 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.109 ms/op
                 existUser·p0.50:   5.210 ms/op
                 existUser·p0.90:   7.504 ms/op
                 existUser·p0.95:   8.552 ms/op
                 existUser·p0.99:   11.518 ms/op
                 existUser·p0.999:  24.183 ms/op
                 existUser·p0.9999: 32.178 ms/op
                 existUser·p1.00:   32.309 ms/op

Iteration   2: 5.312 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.755 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.783 ms/op
                 existUser·p0.95:   7.848 ms/op
                 existUser·p0.99:   10.519 ms/op
                 existUser·p0.999:  24.642 ms/op
                 existUser·p0.9999: 50.463 ms/op
                 existUser·p1.00:   55.050 ms/op

Iteration   3: 5.406 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   7.086 ms/op
                 existUser·p0.95:   8.143 ms/op
                 existUser·p0.99:   11.370 ms/op
                 existUser·p0.999:  27.188 ms/op
                 existUser·p0.9999: 35.783 ms/op
                 existUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176221
  mean =      5.447 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 85457 
    [ 5.000, 10.000) = 87562 
    [10.000, 15.000) = 2741 
    [15.000, 20.000) = 240 
    [20.000, 25.000) = 58 
    [25.000, 30.000) = 75 
    [30.000, 35.000) = 47 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 12 
    [45.000, 50.000) = 12 
    [50.000, 55.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.688 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      7.135 ms/op
     p(95.0000) =      8.208 ms/op
     p(99.0000) =     11.239 ms/op
     p(99.9000) =     24.594 ms/op
     p(99.9900) =     45.482 ms/op
     p(99.9990) =     54.451 ms/op
     p(99.9999) =     55.050 ms/op
    p(100.0000) =     55.050 ms/op


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
# Warmup Iteration   1: 16.707 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 6.649 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.591 ±(99.9%) 0.022 ms/op
Iteration   1: 5.600 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.224 ms/op
                 getUser·p0.50:   5.169 ms/op
                 getUser·p0.90:   7.258 ms/op
                 getUser·p0.95:   8.569 ms/op
                 getUser·p0.99:   13.059 ms/op
                 getUser·p0.999:  23.855 ms/op
                 getUser·p0.9999: 29.304 ms/op
                 getUser·p1.00:   29.786 ms/op

Iteration   2: 5.575 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.159 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.971 ms/op
                 getUser·p0.95:   7.856 ms/op
                 getUser·p0.99:   10.273 ms/op
                 getUser·p0.999:  19.702 ms/op
                 getUser·p0.9999: 28.772 ms/op
                 getUser·p1.00:   29.164 ms/op

Iteration   3: 5.368 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.634 ms/op
                 getUser·p0.50:   4.940 ms/op
                 getUser·p0.90:   6.761 ms/op
                 getUser·p0.95:   7.905 ms/op
                 getUser·p0.99:   10.633 ms/op
                 getUser·p0.999:  25.922 ms/op
                 getUser·p0.9999: 31.692 ms/op
                 getUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174114
  mean =      5.512 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 77233 
    [ 5.000,  7.500) = 84359 
    [ 7.500, 10.000) = 9546 
    [10.000, 12.500) = 1778 
    [12.500, 15.000) = 615 
    [15.000, 17.500) = 227 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.159 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.980 ms/op
     p(95.0000) =      8.126 ms/op
     p(99.0000) =     11.289 ms/op
     p(99.9000) =     23.855 ms/op
     p(99.9900) =     30.740 ms/op
     p(99.9990) =     32.531 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


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
# Warmup Iteration   1: 18.891 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 7.542 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.553 ±(99.9%) 0.025 ms/op
Iteration   1: 6.298 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.732 ms/op
                 listUser·p0.50:   5.906 ms/op
                 listUser·p0.90:   7.905 ms/op
                 listUser·p0.95:   9.016 ms/op
                 listUser·p0.99:   12.184 ms/op
                 listUser·p0.999:  26.351 ms/op
                 listUser·p0.9999: 30.403 ms/op
                 listUser·p1.00:   31.293 ms/op

Iteration   2: 6.587 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.572 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   8.317 ms/op
                 listUser·p0.95:   9.486 ms/op
                 listUser·p0.99:   12.531 ms/op
                 listUser·p0.999:  28.553 ms/op
                 listUser·p0.9999: 31.475 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   3: 6.291 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.314 ms/op
                 listUser·p0.50:   5.710 ms/op
                 listUser·p0.90:   8.290 ms/op
                 listUser·p0.95:   9.552 ms/op
                 listUser·p0.99:   12.812 ms/op
                 listUser·p0.999:  20.174 ms/op
                 listUser·p0.9999: 23.790 ms/op
                 listUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150282
  mean =      6.389 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 10244 
    [ 5.000,  7.500) = 117481 
    [ 7.500, 10.000) = 17282 
    [10.000, 12.500) = 3771 
    [12.500, 15.000) = 960 
    [15.000, 17.500) = 208 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 87 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.572 ms/op
     p(50.0000) =      5.964 ms/op
     p(90.0000) =      8.176 ms/op
     p(95.0000) =      9.388 ms/op
     p(99.0000) =     12.501 ms/op
     p(99.9000) =     26.402 ms/op
     p(99.9900) =     30.277 ms/op
     p(99.9990) =     34.111 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.911 ± 3.415  ops/ms
ClientPb.existUser                       thrpt       3   6.127 ± 2.510  ops/ms
ClientPb.getUser                         thrpt       3   5.929 ± 4.107  ops/ms
ClientPb.listUser                        thrpt       3   4.820 ± 1.965  ops/ms
ClientPb.createUser                       avgt       3   5.513 ± 3.760   ms/op
ClientPb.existUser                        avgt       3   5.154 ± 2.751   ms/op
ClientPb.getUser                          avgt       3   5.559 ± 1.748   ms/op
ClientPb.listUser                         avgt       3   6.235 ± 1.803   ms/op
ClientPb.createUser                     sample  171241   5.600 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.478           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.111           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.036           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.256           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.290           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.240           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.669           ms/op
ClientPb.existUser                      sample  176221   5.447 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.688           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.038           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.135           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.208           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.239           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.594           ms/op
ClientPb.existUser:existUser·p0.9999    sample          45.482           ms/op
ClientPb.existUser:existUser·p1.00      sample          55.050           ms/op
ClientPb.getUser                        sample  174114   5.512 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.159           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.136           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.980           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.126           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.289           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.855           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.740           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.604           ms/op
ClientPb.listUser                       sample  150282   6.389 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.572           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.964           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.176           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.388           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.501           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.402           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.277           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.210           ms/op
