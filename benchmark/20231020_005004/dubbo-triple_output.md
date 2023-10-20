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
# Warmup Iteration   1: 2.416 ops/ms
# Warmup Iteration   2: 6.245 ops/ms
# Warmup Iteration   3: 9.459 ops/ms
Iteration   1: 9.992 ops/ms
Iteration   2: 9.982 ops/ms
Iteration   3: 10.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.022 ±(99.9%) 1.098 ops/ms [Average]
  (min, avg, max) = (9.982, 10.022, 10.091), stdev = 0.060
  CI (99.9%): [8.924, 11.120] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.739 ops/ms
# Warmup Iteration   2: 9.805 ops/ms
# Warmup Iteration   3: 10.202 ops/ms
Iteration   1: 10.472 ops/ms
Iteration   2: 10.416 ops/ms
Iteration   3: 10.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.336 ±(99.9%) 3.465 ops/ms [Average]
  (min, avg, max) = (10.119, 10.336, 10.472), stdev = 0.190
  CI (99.9%): [6.870, 13.801] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.336 ops/ms
# Warmup Iteration   2: 9.402 ops/ms
# Warmup Iteration   3: 9.746 ops/ms
Iteration   1: 10.067 ops/ms
Iteration   2: 10.201 ops/ms
Iteration   3: 10.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.093 ±(99.9%) 1.777 ops/ms [Average]
  (min, avg, max) = (10.011, 10.093, 10.201), stdev = 0.097
  CI (99.9%): [8.316, 11.870] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.251 ops/ms
# Warmup Iteration   2: 7.741 ops/ms
# Warmup Iteration   3: 8.488 ops/ms
Iteration   1: 8.644 ops/ms
Iteration   2: 8.507 ops/ms
Iteration   3: 8.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.555 ±(99.9%) 1.405 ops/ms [Average]
  (min, avg, max) = (8.507, 8.555, 8.644), stdev = 0.077
  CI (99.9%): [7.150, 9.960] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.414 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.395 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.002 ms/op
Iteration   1: 3.330 ±(99.9%) 0.004 ms/op
Iteration   2: 3.205 ±(99.9%) 0.003 ms/op
Iteration   3: 3.151 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.229 ±(99.9%) 1.679 ms/op [Average]
  (min, avg, max) = (3.151, 3.229, 3.330), stdev = 0.092
  CI (99.9%): [1.550, 4.908] (assumes normal distribution)


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
# Warmup Iteration   1: 7.465 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.003 ms/op
Iteration   1: 3.083 ±(99.9%) 0.001 ms/op
Iteration   2: 3.092 ±(99.9%) 0.004 ms/op
Iteration   3: 3.062 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.079 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (3.062, 3.079, 3.092), stdev = 0.015
  CI (99.9%): [2.804, 3.353] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.709 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.004 ms/op
Iteration   1: 3.160 ±(99.9%) 0.004 ms/op
Iteration   2: 3.144 ±(99.9%) 0.003 ms/op
Iteration   3: 3.242 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.182 ±(99.9%) 0.955 ms/op [Average]
  (min, avg, max) = (3.144, 3.182, 3.242), stdev = 0.052
  CI (99.9%): [2.227, 4.137] (assumes normal distribution)


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
# Warmup Iteration   1: 9.091 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.005 ms/op
Iteration   1: 3.774 ±(99.9%) 0.004 ms/op
Iteration   2: 3.821 ±(99.9%) 0.004 ms/op
Iteration   3: 3.840 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.812 ±(99.9%) 0.615 ms/op [Average]
  (min, avg, max) = (3.774, 3.812, 3.840), stdev = 0.034
  CI (99.9%): [3.196, 4.427] (assumes normal distribution)


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
# Warmup Iteration   1: 6.755 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.008 ms/op
Iteration   1: 3.199 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  16.632 ms/op
                 createUser·p0.9999: 20.120 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   2: 3.270 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  18.809 ms/op
                 createUser·p0.9999: 23.025 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   3: 3.242 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  16.076 ms/op
                 createUser·p0.9999: 19.173 ms/op
                 createUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296500
  mean =      3.237 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16038 
    [ 2.500,  5.000) = 275256 
    [ 5.000,  7.500) = 4151 
    [ 7.500, 10.000) = 394 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 178 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     16.187 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     23.201 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 7.250 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.409 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.008 ms/op
Iteration   1: 3.046 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  14.857 ms/op
                 existUser·p0.9999: 20.627 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  13.069 ms/op
                 existUser·p0.9999: 21.064 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  12.489 ms/op
                 existUser·p0.9999: 22.863 ms/op
                 existUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309813
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12959 
    [ 2.500,  5.000) = 292837 
    [ 5.000,  7.500) = 3277 
    [ 7.500, 10.000) = 230 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.527 ms/op
     p(99.0000) =      5.332 ms/op
     p(99.9000) =     13.389 ms/op
     p(99.9900) =     21.300 ms/op
     p(99.9990) =     23.649 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 7.213 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.008 ms/op
Iteration   1: 3.361 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.473 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  16.515 ms/op
                 getUser·p0.9999: 19.758 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  9.036 ms/op
                 getUser·p0.9999: 21.396 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   3: 3.226 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  14.254 ms/op
                 getUser·p0.9999: 20.712 ms/op
                 getUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294678
  mean =      3.255 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12922 
    [ 2.500,  5.000) = 274706 
    [ 5.000,  7.500) = 5954 
    [ 7.500, 10.000) = 432 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     15.756 ms/op
     p(99.9900) =     20.891 ms/op
     p(99.9990) =     21.498 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 8.288 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.009 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.011 ms/op
Iteration   1: 3.783 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.702 ms/op
                 listUser·p0.999:  15.996 ms/op
                 listUser·p0.9999: 20.785 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   2: 3.838 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.937 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.368 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  13.517 ms/op
                 listUser·p0.9999: 15.313 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   3: 3.798 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.056 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 13.894 ms/op
                 listUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252360
  mean =      3.806 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 85 
    [ 2.500,  5.000) = 245664 
    [ 5.000,  7.500) = 5214 
    [ 7.500, 10.000) = 710 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     13.609 ms/op
     p(99.9900) =     19.817 ms/op
     p(99.9990) =     21.248 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.022 ± 1.098  ops/ms
ClientPb.existUser                       thrpt       3  10.336 ± 3.465  ops/ms
ClientPb.getUser                         thrpt       3  10.093 ± 1.777  ops/ms
ClientPb.listUser                        thrpt       3   8.555 ± 1.405  ops/ms
ClientPb.createUser                       avgt       3   3.229 ± 1.679   ms/op
ClientPb.existUser                        avgt       3   3.079 ± 0.274   ms/op
ClientPb.getUser                          avgt       3   3.182 ± 0.955   ms/op
ClientPb.listUser                         avgt       3   3.812 ± 0.615   ms/op
ClientPb.createUser                     sample  296500   3.237 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.114           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.617           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.612           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.187           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.692           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.429           ms/op
ClientPb.existUser                      sample  309813   3.097 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.587           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.332           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.389           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.300           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.150           ms/op
ClientPb.getUser                        sample  294678   3.255 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.106           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.756           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.891           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.856           ms/op
ClientPb.listUser                       sample  252360   3.806 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.149           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.609           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.817           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.299           ms/op
