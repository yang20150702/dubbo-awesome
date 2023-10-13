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
# Warmup Iteration   1: 2.609 ops/ms
# Warmup Iteration   2: 6.565 ops/ms
# Warmup Iteration   3: 9.088 ops/ms
Iteration   1: 9.686 ops/ms
Iteration   2: 9.678 ops/ms
Iteration   3: 9.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.654 ±(99.9%) 0.870 ops/ms [Average]
  (min, avg, max) = (9.600, 9.654, 9.686), stdev = 0.048
  CI (99.9%): [8.785, 10.524] (assumes normal distribution)


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
# Warmup Iteration   1: 3.366 ops/ms
# Warmup Iteration   2: 8.806 ops/ms
# Warmup Iteration   3: 9.988 ops/ms
Iteration   1: 10.151 ops/ms
Iteration   2: 9.981 ops/ms
Iteration   3: 10.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.060 ±(99.9%) 1.564 ops/ms [Average]
  (min, avg, max) = (9.981, 10.060, 10.151), stdev = 0.086
  CI (99.9%): [8.497, 11.624] (assumes normal distribution)


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
# Warmup Iteration   1: 3.251 ops/ms
# Warmup Iteration   2: 8.677 ops/ms
# Warmup Iteration   3: 9.650 ops/ms
Iteration   1: 9.646 ops/ms
Iteration   2: 9.697 ops/ms
Iteration   3: 9.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.744 ±(99.9%) 2.347 ops/ms [Average]
  (min, avg, max) = (9.646, 9.744, 9.890), stdev = 0.129
  CI (99.9%): [7.397, 12.091] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.049 ops/ms
# Warmup Iteration   2: 7.649 ops/ms
# Warmup Iteration   3: 8.142 ops/ms
Iteration   1: 8.165 ops/ms
Iteration   2: 8.233 ops/ms
Iteration   3: 8.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.243 ±(99.9%) 1.507 ops/ms [Average]
  (min, avg, max) = (8.165, 8.243, 8.330), stdev = 0.083
  CI (99.9%): [6.736, 9.750] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.942 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.464 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.004 ms/op
Iteration   1: 3.326 ±(99.9%) 0.004 ms/op
Iteration   2: 3.298 ±(99.9%) 0.004 ms/op
Iteration   3: 3.275 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.300 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (3.275, 3.300, 3.326), stdev = 0.026
  CI (99.9%): [2.831, 3.769] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.918 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.003 ms/op
Iteration   1: 3.228 ±(99.9%) 0.004 ms/op
Iteration   2: 3.183 ±(99.9%) 0.003 ms/op
Iteration   3: 3.190 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.200 ±(99.9%) 0.441 ms/op [Average]
  (min, avg, max) = (3.183, 3.200, 3.228), stdev = 0.024
  CI (99.9%): [2.759, 3.642] (assumes normal distribution)


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
# Warmup Iteration   1: 7.717 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.002 ms/op
Iteration   1: 3.365 ±(99.9%) 0.003 ms/op
Iteration   2: 3.197 ±(99.9%) 0.004 ms/op
Iteration   3: 3.278 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.280 ±(99.9%) 1.537 ms/op [Average]
  (min, avg, max) = (3.197, 3.280, 3.365), stdev = 0.084
  CI (99.9%): [1.743, 4.817] (assumes normal distribution)


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
# Warmup Iteration   1: 8.946 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.008 ms/op
Iteration   1: 3.885 ±(99.9%) 0.006 ms/op
Iteration   2: 3.865 ±(99.9%) 0.006 ms/op
Iteration   3: 3.920 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.890 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (3.865, 3.890, 3.920), stdev = 0.028
  CI (99.9%): [3.386, 4.393] (assumes normal distribution)


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
# Warmup Iteration   1: 8.946 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.106 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.009 ms/op
Iteration   1: 3.389 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  17.416 ms/op
                 createUser·p0.9999: 20.072 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   2: 3.316 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   6.586 ms/op
                 createUser·p0.999:  19.071 ms/op
                 createUser·p0.9999: 22.219 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   3: 3.377 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  21.856 ms/op
                 createUser·p0.9999: 27.100 ms/op
                 createUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285924
  mean =      3.360 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13318 
    [ 2.500,  5.000) = 265591 
    [ 5.000,  7.500) = 5892 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     24.622 ms/op
     p(99.9990) =     27.843 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 8.126 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.009 ms/op
Iteration   1: 3.184 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  16.441 ms/op
                 existUser·p0.9999: 21.494 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 3.178 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  19.870 ms/op
                 existUser·p0.9999: 23.296 ms/op
                 existUser·p1.00:   23.527 ms/op

Iteration   3: 3.222 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  15.118 ms/op
                 existUser·p0.9999: 21.143 ms/op
                 existUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300291
  mean =      3.195 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15161 
    [ 2.500,  5.000) = 277536 
    [ 5.000,  7.500) = 6681 
    [ 7.500, 10.000) = 422 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     15.335 ms/op
     p(99.9900) =     22.380 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 8.324 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.559 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.011 ms/op
Iteration   1: 3.380 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   5.276 ms/op
                 getUser·p0.99:   6.799 ms/op
                 getUser·p0.999:  17.863 ms/op
                 getUser·p0.9999: 30.673 ms/op
                 getUser·p1.00:   34.013 ms/op

Iteration   2: 3.258 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  15.932 ms/op
                 getUser·p0.9999: 21.142 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   3: 3.283 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  16.286 ms/op
                 getUser·p0.9999: 21.539 ms/op
                 getUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290120
  mean =      3.306 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13067 
    [ 2.500,  5.000) = 267240 
    [ 5.000,  7.500) = 8398 
    [ 7.500, 10.000) = 736 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     16.739 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     32.581 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 8.310 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.013 ms/op
Iteration   1: 3.975 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.636 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  18.000 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   2: 3.942 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.702 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   8.525 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 30.540 ms/op
                 listUser·p1.00:   31.162 ms/op

Iteration   3: 3.869 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.722 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   8.053 ms/op
                 listUser·p0.999:  12.534 ms/op
                 listUser·p0.9999: 14.797 ms/op
                 listUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244469
  mean =      3.928 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 216 
    [ 2.500,  5.000) = 235119 
    [ 5.000,  7.500) = 6270 
    [ 7.500, 10.000) = 1894 
    [10.000, 12.500) = 396 
    [12.500, 15.000) = 374 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     31.020 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.654 ± 0.870  ops/ms
ClientPb.existUser                       thrpt       3  10.060 ± 1.564  ops/ms
ClientPb.getUser                         thrpt       3   9.744 ± 2.347  ops/ms
ClientPb.listUser                        thrpt       3   8.243 ± 1.507  ops/ms
ClientPb.createUser                       avgt       3   3.300 ± 0.469   ms/op
ClientPb.existUser                        avgt       3   3.200 ± 0.441   ms/op
ClientPb.getUser                          avgt       3   3.280 ± 1.537   ms/op
ClientPb.listUser                         avgt       3   3.890 ± 0.504   ms/op
ClientPb.createUser                     sample  285924   3.360 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.027           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.455           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.579           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.622           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.115           ms/op
ClientPb.existUser                      sample  300291   3.195 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.807           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.185           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.335           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.380           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.527           ms/op
ClientPb.getUser                        sample  290120   3.306 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.421           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.690           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.141           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.586           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.739           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.426           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.013           ms/op
ClientPb.listUser                       sample  244469   3.928 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.702           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.789           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.864           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.680           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.426           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.162           ms/op
