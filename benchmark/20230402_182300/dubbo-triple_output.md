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
# Warmup Iteration   1: 2.734 ops/ms
# Warmup Iteration   2: 6.546 ops/ms
# Warmup Iteration   3: 9.184 ops/ms
Iteration   1: 10.173 ops/ms
Iteration   2: 9.986 ops/ms
Iteration   3: 9.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.990 ±(99.9%) 3.316 ops/ms [Average]
  (min, avg, max) = (9.810, 9.990, 10.173), stdev = 0.182
  CI (99.9%): [6.674, 13.306] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ops/ms
# Warmup Iteration   2: 9.297 ops/ms
# Warmup Iteration   3: 10.092 ops/ms
Iteration   1: 10.373 ops/ms
Iteration   2: 10.218 ops/ms
Iteration   3: 10.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.281 ±(99.9%) 1.490 ops/ms [Average]
  (min, avg, max) = (10.218, 10.281, 10.373), stdev = 0.082
  CI (99.9%): [8.791, 11.771] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.340 ops/ms
# Warmup Iteration   2: 9.523 ops/ms
# Warmup Iteration   3: 9.826 ops/ms
Iteration   1: 10.248 ops/ms
Iteration   2: 9.642 ops/ms
Iteration   3: 9.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.907 ±(99.9%) 5.659 ops/ms [Average]
  (min, avg, max) = (9.642, 9.907, 10.248), stdev = 0.310
  CI (99.9%): [4.248, 15.565] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.529 ops/ms
# Warmup Iteration   2: 7.895 ops/ms
# Warmup Iteration   3: 8.203 ops/ms
Iteration   1: 8.422 ops/ms
Iteration   2: 8.542 ops/ms
Iteration   3: 8.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.502 ±(99.9%) 1.259 ops/ms [Average]
  (min, avg, max) = (8.422, 8.502, 8.542), stdev = 0.069
  CI (99.9%): [7.243, 9.761] (assumes normal distribution)


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
# Warmup Iteration   1: 7.282 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.003 ms/op
Iteration   1: 3.250 ±(99.9%) 0.007 ms/op
Iteration   2: 3.211 ±(99.9%) 0.003 ms/op
Iteration   3: 3.101 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.187 ±(99.9%) 1.412 ms/op [Average]
  (min, avg, max) = (3.101, 3.187, 3.250), stdev = 0.077
  CI (99.9%): [1.775, 4.600] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.869 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
Iteration   1: 3.079 ±(99.9%) 0.004 ms/op
Iteration   2: 3.049 ±(99.9%) 0.004 ms/op
Iteration   3: 3.166 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.098 ±(99.9%) 1.109 ms/op [Average]
  (min, avg, max) = (3.049, 3.098, 3.166), stdev = 0.061
  CI (99.9%): [1.989, 4.208] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.494 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.002 ms/op
Iteration   1: 3.229 ±(99.9%) 0.003 ms/op
Iteration   2: 3.067 ±(99.9%) 0.007 ms/op
Iteration   3: 3.069 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.122 ±(99.9%) 1.702 ms/op [Average]
  (min, avg, max) = (3.067, 3.122, 3.229), stdev = 0.093
  CI (99.9%): [1.420, 4.824] (assumes normal distribution)


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
# Warmup Iteration   1: 9.649 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.007 ms/op
Iteration   1: 3.662 ±(99.9%) 0.005 ms/op
Iteration   2: 3.761 ±(99.9%) 0.003 ms/op
Iteration   3: 3.699 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.707 ±(99.9%) 0.905 ms/op [Average]
  (min, avg, max) = (3.662, 3.707, 3.761), stdev = 0.050
  CI (99.9%): [2.802, 4.613] (assumes normal distribution)


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
# Warmup Iteration   1: 7.803 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.010 ms/op
Iteration   1: 3.136 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.559 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  9.863 ms/op
                 createUser·p0.9999: 23.154 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.541 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  15.008 ms/op
                 createUser·p0.9999: 24.136 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.619 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  14.533 ms/op
                 createUser·p0.9999: 18.960 ms/op
                 createUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 307960
  mean =      3.116 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9761 
    [ 2.500,  5.000) = 293704 
    [ 5.000,  7.500) = 3659 
    [ 7.500, 10.000) = 419 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     25.024 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 6.848 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.012 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  10.578 ms/op
                 existUser·p0.9999: 22.574 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 3.021 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.994 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  13.074 ms/op
                 existUser·p0.9999: 21.477 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.375 ms/op
                 existUser·p0.99:   4.719 ms/op
                 existUser·p0.999:  13.304 ms/op
                 existUser·p0.9999: 19.145 ms/op
                 existUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 319508
  mean =      3.001 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12153 
    [ 2.500,  5.000) = 302697 
    [ 5.000,  7.500) = 3866 
    [ 7.500, 10.000) = 390 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.236 ms/op
     p(95.0000) =      3.478 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     21.366 ms/op
     p(99.9990) =     22.964 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 7.856 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.379 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.010 ms/op
Iteration   1: 3.255 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  15.303 ms/op
                 getUser·p0.9999: 18.001 ms/op
                 getUser·p1.00:   19.235 ms/op

Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.597 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  8.733 ms/op
                 getUser·p0.9999: 20.086 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  9.241 ms/op
                 getUser·p0.9999: 20.175 ms/op
                 getUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301594
  mean =      3.182 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11873 
    [ 2.500,  5.000) = 282471 
    [ 5.000,  7.500) = 6404 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     14.205 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     21.330 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


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
# Warmup Iteration   1: 8.654 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.670 ±(99.9%) 0.011 ms/op
Iteration   1: 3.609 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   3.711 ms/op
                 listUser·p0.95:   4.059 ms/op
                 listUser·p0.99:   6.193 ms/op
                 listUser·p0.999:  14.759 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   2: 3.752 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.573 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  13.713 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   3: 3.732 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  11.567 ms/op
                 listUser·p0.9999: 13.353 ms/op
                 listUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259404
  mean =      3.697 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 88 
    [ 2.500,  5.000) = 251945 
    [ 5.000,  7.500) = 5435 
    [ 7.500, 10.000) = 1279 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.990 ± 3.316  ops/ms
ClientPb.existUser                       thrpt       3  10.281 ± 1.490  ops/ms
ClientPb.getUser                         thrpt       3   9.907 ± 5.659  ops/ms
ClientPb.listUser                        thrpt       3   8.502 ± 1.259  ops/ms
ClientPb.createUser                       avgt       3   3.187 ± 1.412   ms/op
ClientPb.existUser                        avgt       3   3.098 ± 1.109   ms/op
ClientPb.getUser                          avgt       3   3.122 ± 1.702   ms/op
ClientPb.listUser                         avgt       3   3.707 ± 0.905   ms/op
ClientPb.createUser                     sample  307960   3.116 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.883           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.986           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.506           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.533           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.233           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.149           ms/op
ClientPb.existUser                      sample  319508   3.001 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.994           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.900           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.058           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.366           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.069           ms/op
ClientPb.getUser                        sample  301594   3.182 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.335           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.205           ms/op
ClientPb.getUser:getUser·p0.9999        sample          19.956           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.512           ms/op
ClientPb.listUser                       sample  259404   3.697 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.550           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.963           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.730           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.004           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.135           ms/op
