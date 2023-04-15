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
# Warmup Iteration   1: 2.671 ops/ms
# Warmup Iteration   2: 6.507 ops/ms
# Warmup Iteration   3: 9.242 ops/ms
Iteration   1: 9.778 ops/ms
Iteration   2: 10.104 ops/ms
Iteration   3: 10.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.998 ±(99.9%) 3.464 ops/ms [Average]
  (min, avg, max) = (9.778, 9.998, 10.111), stdev = 0.190
  CI (99.9%): [6.534, 13.462] (assumes normal distribution)


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
# Warmup Iteration   1: 3.921 ops/ms
# Warmup Iteration   2: 9.381 ops/ms
# Warmup Iteration   3: 10.136 ops/ms
Iteration   1: 10.151 ops/ms
Iteration   2: 10.341 ops/ms
Iteration   3: 10.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.356 ±(99.9%) 3.894 ops/ms [Average]
  (min, avg, max) = (10.151, 10.356, 10.577), stdev = 0.213
  CI (99.9%): [6.462, 14.251] (assumes normal distribution)


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
# Warmup Iteration   1: 3.807 ops/ms
# Warmup Iteration   2: 9.038 ops/ms
# Warmup Iteration   3: 9.840 ops/ms
Iteration   1: 9.981 ops/ms
Iteration   2: 10.080 ops/ms
Iteration   3: 9.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.900 ±(99.9%) 4.212 ops/ms [Average]
  (min, avg, max) = (9.640, 9.900, 10.080), stdev = 0.231
  CI (99.9%): [5.688, 14.113] (assumes normal distribution)


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
# Warmup Iteration   1: 3.096 ops/ms
# Warmup Iteration   2: 7.706 ops/ms
# Warmup Iteration   3: 8.350 ops/ms
Iteration   1: 8.567 ops/ms
Iteration   2: 8.541 ops/ms
Iteration   3: 8.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.613 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (8.541, 8.613, 8.732), stdev = 0.104
  CI (99.9%): [6.717, 10.509] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.488 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.007 ms/op
Iteration   1: 3.197 ±(99.9%) 0.006 ms/op
Iteration   2: 3.130 ±(99.9%) 0.002 ms/op
Iteration   3: 3.036 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.121 ±(99.9%) 1.478 ms/op [Average]
  (min, avg, max) = (3.036, 3.121, 3.197), stdev = 0.081
  CI (99.9%): [1.643, 4.598] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.523 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.002 ms/op
Iteration   1: 3.116 ±(99.9%) 0.009 ms/op
Iteration   2: 3.118 ±(99.9%) 0.008 ms/op
Iteration   3: 3.004 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.079 ±(99.9%) 1.185 ms/op [Average]
  (min, avg, max) = (3.004, 3.079, 3.118), stdev = 0.065
  CI (99.9%): [1.895, 4.264] (assumes normal distribution)


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
# Warmup Iteration   1: 7.816 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.508 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.005 ms/op
Iteration   1: 3.292 ±(99.9%) 0.005 ms/op
Iteration   2: 3.148 ±(99.9%) 0.003 ms/op
Iteration   3: 3.062 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.168 ±(99.9%) 2.121 ms/op [Average]
  (min, avg, max) = (3.062, 3.168, 3.292), stdev = 0.116
  CI (99.9%): [1.047, 5.288] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.679 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.007 ms/op
Iteration   1: 3.818 ±(99.9%) 0.004 ms/op
Iteration   2: 3.751 ±(99.9%) 0.004 ms/op
Iteration   3: 3.777 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.782 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (3.751, 3.782, 3.818), stdev = 0.034
  CI (99.9%): [3.170, 4.393] (assumes normal distribution)


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
# Warmup Iteration   1: 7.290 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
Iteration   1: 3.160 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  15.074 ms/op
                 createUser·p0.9999: 29.164 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   2: 3.255 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.546 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  16.294 ms/op
                 createUser·p0.9999: 19.726 ms/op
                 createUser·p1.00:   20.152 ms/op

Iteration   3: 3.089 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  17.252 ms/op
                 createUser·p0.9999: 28.246 ms/op
                 createUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303012
  mean =      3.166 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11311 
    [ 2.500,  5.000) = 285949 
    [ 5.000,  7.500) = 4783 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     29.721 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.882 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.007 ms/op
Iteration   1: 3.086 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  9.929 ms/op
                 existUser·p0.9999: 24.728 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   2: 3.066 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.481 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.240 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  14.893 ms/op
                 existUser·p0.9999: 21.398 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   4.863 ms/op
                 existUser·p0.999:  9.613 ms/op
                 existUser·p0.9999: 18.002 ms/op
                 existUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314049
  mean =      3.054 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30186 
    [ 2.500,  5.000) = 279128 
    [ 5.000,  7.500) = 3930 
    [ 7.500, 10.000) = 405 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.211 ms/op
     p(95.0000) =      3.379 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     11.908 ms/op
     p(99.9900) =     23.055 ms/op
     p(99.9990) =     24.768 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 8.116 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.425 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.010 ms/op
Iteration   1: 3.237 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.799 ms/op
                 getUser·p0.999:  16.346 ms/op
                 getUser·p0.9999: 20.517 ms/op
                 getUser·p1.00:   21.496 ms/op

Iteration   2: 3.189 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  8.897 ms/op
                 getUser·p0.9999: 29.359 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   3: 3.298 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  12.615 ms/op
                 getUser·p0.9999: 20.588 ms/op
                 getUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296139
  mean =      3.241 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13623 
    [ 2.500,  5.000) = 272267 
    [ 5.000,  7.500) = 8994 
    [ 7.500, 10.000) = 731 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     12.878 ms/op
     p(99.9900) =     27.276 ms/op
     p(99.9990) =     29.660 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 8.977 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.125 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.013 ms/op
Iteration   1: 3.807 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.755 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  14.222 ms/op
                 listUser·p0.9999: 19.098 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   2: 3.802 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  14.647 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   3: 3.813 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.177 ms/op
                 listUser·p0.999:  12.698 ms/op
                 listUser·p0.9999: 18.153 ms/op
                 listUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252098
  mean =      3.807 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 243585 
    [ 5.000,  7.500) = 6396 
    [ 7.500, 10.000) = 1392 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.755 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     13.877 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.998 ± 3.464  ops/ms
ClientPb.existUser                       thrpt       3  10.356 ± 3.894  ops/ms
ClientPb.getUser                         thrpt       3   9.900 ± 4.212  ops/ms
ClientPb.listUser                        thrpt       3   8.613 ± 1.896  ops/ms
ClientPb.createUser                       avgt       3   3.121 ± 1.478   ms/op
ClientPb.existUser                        avgt       3   3.079 ± 1.185   ms/op
ClientPb.getUser                          avgt       3   3.168 ± 2.121   ms/op
ClientPb.listUser                         avgt       3   3.782 ± 0.611   ms/op
ClientPb.createUser                     sample  303012   3.166 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.815           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.621           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.777           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.246           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.753           ms/op
ClientPb.existUser                      sample  314049   3.054 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.147           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.251           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.908           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.055           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.773           ms/op
ClientPb.getUser                        sample  296139   3.241 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.898           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.878           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.276           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.917           ms/op
ClientPb.listUser                       sample  252098   3.807 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.755           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.234           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.877           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.038           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.021           ms/op
