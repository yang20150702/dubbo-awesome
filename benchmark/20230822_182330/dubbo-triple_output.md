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
# Warmup Iteration   1: 2.488 ops/ms
# Warmup Iteration   2: 6.044 ops/ms
# Warmup Iteration   3: 9.411 ops/ms
Iteration   1: 9.856 ops/ms
Iteration   2: 9.752 ops/ms
Iteration   3: 9.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.808 ±(99.9%) 0.960 ops/ms [Average]
  (min, avg, max) = (9.752, 9.808, 9.856), stdev = 0.053
  CI (99.9%): [8.848, 10.768] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.146 ops/ms
# Warmup Iteration   2: 9.643 ops/ms
# Warmup Iteration   3: 10.138 ops/ms
Iteration   1: 10.426 ops/ms
Iteration   2: 10.259 ops/ms
Iteration   3: 10.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.271 ±(99.9%) 2.720 ops/ms [Average]
  (min, avg, max) = (10.128, 10.271, 10.426), stdev = 0.149
  CI (99.9%): [7.550, 12.991] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.510 ops/ms
# Warmup Iteration   2: 9.457 ops/ms
# Warmup Iteration   3: 9.688 ops/ms
Iteration   1: 9.684 ops/ms
Iteration   2: 9.697 ops/ms
Iteration   3: 9.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.745 ±(99.9%) 1.736 ops/ms [Average]
  (min, avg, max) = (9.684, 9.745, 9.855), stdev = 0.095
  CI (99.9%): [8.010, 11.481] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.501 ops/ms
# Warmup Iteration   2: 7.814 ops/ms
# Warmup Iteration   3: 8.277 ops/ms
Iteration   1: 8.697 ops/ms
Iteration   2: 8.350 ops/ms
Iteration   3: 8.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.528 ±(99.9%) 3.170 ops/ms [Average]
  (min, avg, max) = (8.350, 8.528, 8.697), stdev = 0.174
  CI (99.9%): [5.358, 11.698] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.282 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.004 ms/op
Iteration   1: 3.295 ±(99.9%) 0.004 ms/op
Iteration   2: 3.263 ±(99.9%) 0.005 ms/op
Iteration   3: 3.172 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.243 ±(99.9%) 1.170 ms/op [Average]
  (min, avg, max) = (3.172, 3.243, 3.295), stdev = 0.064
  CI (99.9%): [2.073, 4.414] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.957 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.393 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.003 ms/op
Iteration   1: 3.255 ±(99.9%) 0.005 ms/op
Iteration   2: 3.094 ±(99.9%) 0.003 ms/op
Iteration   3: 3.099 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.149 ±(99.9%) 1.670 ms/op [Average]
  (min, avg, max) = (3.094, 3.149, 3.255), stdev = 0.092
  CI (99.9%): [1.479, 4.819] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.066 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.523 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.003 ms/op
Iteration   1: 3.321 ±(99.9%) 0.004 ms/op
Iteration   2: 3.282 ±(99.9%) 0.006 ms/op
Iteration   3: 3.161 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.255 ±(99.9%) 1.528 ms/op [Average]
  (min, avg, max) = (3.161, 3.255, 3.321), stdev = 0.084
  CI (99.9%): [1.727, 4.782] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.915 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.003 ms/op
Iteration   1: 3.792 ±(99.9%) 0.008 ms/op
Iteration   2: 3.786 ±(99.9%) 0.005 ms/op
Iteration   3: 3.790 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.789 ±(99.9%) 0.057 ms/op [Average]
  (min, avg, max) = (3.786, 3.789, 3.792), stdev = 0.003
  CI (99.9%): [3.732, 3.846] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.233 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.010 ms/op
Iteration   1: 3.343 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  17.603 ms/op
                 createUser·p0.9999: 23.686 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   2: 3.324 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  19.661 ms/op
                 createUser·p0.9999: 23.008 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 3.212 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  16.332 ms/op
                 createUser·p0.9999: 21.801 ms/op
                 createUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291350
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10083 
    [ 2.500,  5.000) = 274993 
    [ 5.000,  7.500) = 4940 
    [ 7.500, 10.000) = 904 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.339 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.009 ms/op
Iteration   1: 3.188 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.444 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   5.671 ms/op
                 existUser·p0.999:  9.861 ms/op
                 existUser·p0.9999: 29.262 ms/op
                 existUser·p1.00:   30.147 ms/op

Iteration   2: 3.135 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.264 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.730 ms/op
                 existUser·p0.999:  10.829 ms/op
                 existUser·p0.9999: 26.529 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   3: 3.267 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  14.303 ms/op
                 existUser·p0.9999: 23.600 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300219
  mean =      3.196 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13484 
    [ 2.500,  5.000) = 278828 
    [ 5.000,  7.500) = 6593 
    [ 7.500, 10.000) = 819 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     13.821 ms/op
     p(99.9900) =     27.229 ms/op
     p(99.9990) =     29.983 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.383 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.011 ms/op
Iteration   1: 3.439 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  17.039 ms/op
                 getUser·p0.9999: 20.372 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 3.149 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.393 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  14.107 ms/op
                 getUser·p0.9999: 26.242 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   3: 3.332 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.671 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  15.698 ms/op
                 getUser·p0.9999: 26.359 ms/op
                 getUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290572
  mean =      3.302 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20532 
    [ 2.500,  5.000) = 259048 
    [ 5.000,  7.500) = 9432 
    [ 7.500, 10.000) = 1059 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     15.605 ms/op
     p(99.9900) =     25.819 ms/op
     p(99.9990) =     27.201 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.968 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.011 ms/op
Iteration   1: 3.864 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  17.871 ms/op
                 listUser·p0.9999: 25.091 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 3.815 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.395 ms/op
                 listUser·p0.999:  14.375 ms/op
                 listUser·p0.9999: 16.197 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   3: 3.781 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.819 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  13.449 ms/op
                 listUser·p0.9999: 18.055 ms/op
                 listUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251291
  mean =      3.819 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 240966 
    [ 5.000,  7.500) = 7658 
    [ 7.500, 10.000) = 1880 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 261 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     14.462 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     25.672 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.808 ± 0.960  ops/ms
ClientPb.existUser                       thrpt       3  10.271 ± 2.720  ops/ms
ClientPb.getUser                         thrpt       3   9.745 ± 1.736  ops/ms
ClientPb.listUser                        thrpt       3   8.528 ± 3.170  ops/ms
ClientPb.createUser                       avgt       3   3.243 ± 1.170   ms/op
ClientPb.existUser                        avgt       3   3.149 ± 1.670   ms/op
ClientPb.getUser                          avgt       3   3.255 ± 1.528   ms/op
ClientPb.listUser                         avgt       3   3.789 ± 0.057   ms/op
ClientPb.createUser                     sample  291350   3.292 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.071           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.924           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.134           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.379           ms/op
ClientPb.existUser                      sample  300219   3.196 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.006           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.104           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.821           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.229           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.147           ms/op
ClientPb.getUser                        sample  290572   3.302 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.227           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.562           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.605           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.819           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.361           ms/op
ClientPb.listUser                       sample  251291   3.819 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.460           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.537           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.462           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.281           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.821           ms/op
