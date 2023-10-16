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
# Warmup Iteration   1: 1.550 ops/ms
# Warmup Iteration   2: 3.144 ops/ms
# Warmup Iteration   3: 6.472 ops/ms
Iteration   1: 7.228 ops/ms
Iteration   2: 7.702 ops/ms
Iteration   3: 7.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.548 ±(99.9%) 5.049 ops/ms [Average]
  (min, avg, max) = (7.228, 7.548, 7.712), stdev = 0.277
  CI (99.9%): [2.498, 12.597] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 2.168 ops/ms
# Warmup Iteration   2: 6.845 ops/ms
# Warmup Iteration   3: 7.522 ops/ms
Iteration   1: 8.140 ops/ms
Iteration   2: 8.172 ops/ms
Iteration   3: 8.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.109 ±(99.9%) 1.504 ops/ms [Average]
  (min, avg, max) = (8.016, 8.109, 8.172), stdev = 0.082
  CI (99.9%): [6.605, 9.613] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.032 ops/ms
# Warmup Iteration   2: 6.235 ops/ms
# Warmup Iteration   3: 7.613 ops/ms
Iteration   1: 7.811 ops/ms
Iteration   2: 7.742 ops/ms
Iteration   3: 7.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.825 ±(99.9%) 1.647 ops/ms [Average]
  (min, avg, max) = (7.742, 7.825, 7.921), stdev = 0.090
  CI (99.9%): [6.178, 9.472] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.014 ops/ms
# Warmup Iteration   2: 5.455 ops/ms
# Warmup Iteration   3: 6.163 ops/ms
Iteration   1: 6.092 ops/ms
Iteration   2: 6.398 ops/ms
Iteration   3: 6.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.240 ±(99.9%) 2.795 ops/ms [Average]
  (min, avg, max) = (6.092, 6.240, 6.398), stdev = 0.153
  CI (99.9%): [3.444, 9.035] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 15.019 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.263 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.402 ±(99.9%) 0.006 ms/op
Iteration   1: 4.131 ±(99.9%) 0.013 ms/op
Iteration   2: 4.024 ±(99.9%) 0.006 ms/op
Iteration   3: 4.115 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.090 ±(99.9%) 1.055 ms/op [Average]
  (min, avg, max) = (4.024, 4.090, 4.131), stdev = 0.058
  CI (99.9%): [3.035, 5.145] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 15.013 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.805 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.006 ms/op
Iteration   1: 4.302 ±(99.9%) 0.007 ms/op
Iteration   2: 3.974 ±(99.9%) 0.003 ms/op
Iteration   3: 3.945 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.074 ±(99.9%) 3.617 ms/op [Average]
  (min, avg, max) = (3.945, 4.074, 4.302), stdev = 0.198
  CI (99.9%): [0.457, 7.691] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 15.314 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.181 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.447 ±(99.9%) 0.002 ms/op
Iteration   1: 4.164 ±(99.9%) 0.004 ms/op
Iteration   2: 4.204 ±(99.9%) 0.005 ms/op
Iteration   3: 4.120 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.163 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (4.120, 4.163, 4.204), stdev = 0.042
  CI (99.9%): [3.394, 4.931] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 15.635 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.131 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.011 ±(99.9%) 0.008 ms/op
Iteration   1: 5.034 ±(99.9%) 0.007 ms/op
Iteration   2: 4.845 ±(99.9%) 0.006 ms/op
Iteration   3: 5.034 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.971 ±(99.9%) 1.989 ms/op [Average]
  (min, avg, max) = (4.845, 4.971, 5.034), stdev = 0.109
  CI (99.9%): [2.983, 6.960] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 14.991 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 5.615 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.537 ±(99.9%) 0.019 ms/op
Iteration   1: 4.151 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.025 ms/op
                 createUser·p0.50:   4.010 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  20.120 ms/op
                 createUser·p0.9999: 22.217 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   2: 4.187 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.025 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   7.971 ms/op
                 createUser·p0.999:  21.463 ms/op
                 createUser·p0.9999: 24.510 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   3: 4.153 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.985 ms/op
                 createUser·p0.50:   4.043 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   7.365 ms/op
                 createUser·p0.999:  23.986 ms/op
                 createUser·p0.9999: 26.716 ms/op
                 createUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 230305
  mean =      4.164 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 228 
    [ 2.500,  5.000) = 216546 
    [ 5.000,  7.500) = 10563 
    [ 7.500, 10.000) = 1902 
    [10.000, 12.500) = 523 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 156 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.985 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      8.110 ms/op
     p(99.9000) =     21.224 ms/op
     p(99.9900) =     25.493 ms/op
     p(99.9990) =     27.092 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 14.570 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 4.595 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.014 ms/op
Iteration   1: 4.012 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.708 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.497 ms/op
                 existUser·p0.99:   8.176 ms/op
                 existUser·p0.999:  12.555 ms/op
                 existUser·p0.9999: 28.053 ms/op
                 existUser·p1.00:   28.672 ms/op

Iteration   2: 3.884 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   6.889 ms/op
                 existUser·p0.999:  24.533 ms/op
                 existUser·p0.9999: 30.901 ms/op
                 existUser·p1.00:   32.539 ms/op

Iteration   3: 4.135 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.390 ms/op
                 existUser·p0.50:   3.908 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.652 ms/op
                 existUser·p0.99:   8.929 ms/op
                 existUser·p0.999:  16.761 ms/op
                 existUser·p0.9999: 31.007 ms/op
                 existUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 239377
  mean =      4.008 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 317 
    [ 2.500,  5.000) = 222934 
    [ 5.000,  7.500) = 12735 
    [ 7.500, 10.000) = 2406 
    [10.000, 12.500) = 488 
    [12.500, 15.000) = 205 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 97 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.390 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      8.071 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     29.897 ms/op
     p(99.9990) =     32.337 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 15.045 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.077 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.282 ±(99.9%) 0.016 ms/op
Iteration   1: 4.356 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.581 ms/op
                 getUser·p0.50:   4.014 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   7.324 ms/op
                 getUser·p0.99:   9.667 ms/op
                 getUser·p0.999:  15.433 ms/op
                 getUser·p0.9999: 28.901 ms/op
                 getUser·p1.00:   29.491 ms/op

Iteration   2: 4.024 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.597 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   7.351 ms/op
                 getUser·p0.999:  15.041 ms/op
                 getUser·p0.9999: 28.217 ms/op
                 getUser·p1.00:   29.000 ms/op

Iteration   3: 4.101 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.743 ms/op
                 getUser·p0.50:   3.985 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  26.865 ms/op
                 getUser·p0.9999: 29.216 ms/op
                 getUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 231025
  mean =      4.156 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 217786 
    [ 5.000,  7.500) = 8254 
    [ 7.500, 10.000) = 3832 
    [10.000, 12.500) = 665 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 108 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      8.880 ms/op
     p(99.9000) =     15.874 ms/op
     p(99.9900) =     28.901 ms/op
     p(99.9990) =     29.776 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 17.672 ±(99.9%) 0.262 ms/op
# Warmup Iteration   2: 6.711 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.142 ±(99.9%) 0.020 ms/op
Iteration   1: 4.886 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.152 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  25.821 ms/op
                 listUser·p0.9999: 28.049 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   2: 5.143 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   6.914 ms/op
                 listUser·p0.99:   10.671 ms/op
                 listUser·p0.999:  21.676 ms/op
                 listUser·p0.9999: 37.538 ms/op
                 listUser·p1.00:   38.535 ms/op

Iteration   3: 4.984 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   4.833 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  17.727 ms/op
                 listUser·p0.9999: 19.909 ms/op
                 listUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 191852
  mean =      5.002 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 129187 
    [ 5.000,  7.500) = 56662 
    [ 7.500, 10.000) = 4393 
    [10.000, 12.500) = 822 
    [12.500, 15.000) = 314 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.647 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      5.562 ms/op
     p(95.0000) =      6.365 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     21.231 ms/op
     p(99.9900) =     35.943 ms/op
     p(99.9990) =     38.475 ms/op
     p(99.9999) =     38.535 ms/op
    p(100.0000) =     38.535 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.548 ± 5.049  ops/ms
ClientPb.existUser                       thrpt       3   8.109 ± 1.504  ops/ms
ClientPb.getUser                         thrpt       3   7.825 ± 1.647  ops/ms
ClientPb.listUser                        thrpt       3   6.240 ± 2.795  ops/ms
ClientPb.createUser                       avgt       3   4.090 ± 1.055   ms/op
ClientPb.existUser                        avgt       3   4.074 ± 3.617   ms/op
ClientPb.getUser                          avgt       3   4.163 ± 0.768   ms/op
ClientPb.listUser                         avgt       3   4.971 ± 1.989   ms/op
ClientPb.createUser                     sample  230305   4.164 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.985           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.661           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.136           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.110           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.224           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.493           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.263           ms/op
ClientPb.existUser                      sample  239377   4.008 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.390           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.596           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.071           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.531           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.897           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.539           ms/op
ClientPb.getUser                        sample  231025   4.156 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.581           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.226           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.880           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.874           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.901           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.786           ms/op
ClientPb.listUser                       sample  191852   5.002 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.647           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.365           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.519           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.231           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.943           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.535           ms/op
