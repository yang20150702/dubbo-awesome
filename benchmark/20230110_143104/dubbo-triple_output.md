# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.686 ops/ms
# Warmup Iteration   2: 5.754 ops/ms
# Warmup Iteration   3: 9.765 ops/ms
Iteration   1: 9.885 ops/ms
Iteration   2: 9.841 ops/ms
Iteration   3: 10.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.942 ±(99.9%) 2.549 ops/ms [Average]
  (min, avg, max) = (9.841, 9.942, 10.102), stdev = 0.140
  CI (99.9%): [7.394, 12.491] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.375 ops/ms
# Warmup Iteration   2: 9.525 ops/ms
# Warmup Iteration   3: 10.110 ops/ms
Iteration   1: 10.060 ops/ms
Iteration   2: 10.460 ops/ms
Iteration   3: 10.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.411 ±(99.9%) 6.010 ops/ms [Average]
  (min, avg, max) = (10.060, 10.411, 10.713), stdev = 0.329
  CI (99.9%): [4.401, 16.421] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.559 ops/ms
# Warmup Iteration   2: 8.920 ops/ms
# Warmup Iteration   3: 9.855 ops/ms
Iteration   1: 10.078 ops/ms
Iteration   2: 10.021 ops/ms
Iteration   3: 10.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.076 ±(99.9%) 0.983 ops/ms [Average]
  (min, avg, max) = (10.021, 10.076, 10.129), stdev = 0.054
  CI (99.9%): [9.093, 11.059] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.441 ops/ms
# Warmup Iteration   2: 7.685 ops/ms
# Warmup Iteration   3: 8.328 ops/ms
Iteration   1: 8.496 ops/ms
Iteration   2: 8.607 ops/ms
Iteration   3: 8.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.654 ±(99.9%) 3.392 ops/ms [Average]
  (min, avg, max) = (8.496, 8.654, 8.859), stdev = 0.186
  CI (99.9%): [5.262, 12.046] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.065 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.467 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.003 ms/op
Iteration   1: 3.126 ±(99.9%) 0.007 ms/op
Iteration   2: 3.160 ±(99.9%) 0.006 ms/op
Iteration   3: 3.269 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.185 ±(99.9%) 1.363 ms/op [Average]
  (min, avg, max) = (3.126, 3.185, 3.269), stdev = 0.075
  CI (99.9%): [1.821, 4.548] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.740 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.003 ms/op
Iteration   1: 3.074 ±(99.9%) 0.007 ms/op
Iteration   2: 3.064 ±(99.9%) 0.004 ms/op
Iteration   3: 2.993 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.044 ±(99.9%) 0.803 ms/op [Average]
  (min, avg, max) = (2.993, 3.044, 3.074), stdev = 0.044
  CI (99.9%): [2.240, 3.847] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.911 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.003 ms/op
Iteration   1: 3.349 ±(99.9%) 0.005 ms/op
Iteration   2: 3.172 ±(99.9%) 0.006 ms/op
Iteration   3: 3.185 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.236 ±(99.9%) 1.798 ms/op [Average]
  (min, avg, max) = (3.172, 3.236, 3.349), stdev = 0.099
  CI (99.9%): [1.437, 5.034] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.413 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.006 ms/op
Iteration   1: 3.831 ±(99.9%) 0.005 ms/op
Iteration   2: 3.711 ±(99.9%) 0.009 ms/op
Iteration   3: 3.766 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.770 ±(99.9%) 1.092 ms/op [Average]
  (min, avg, max) = (3.711, 3.770, 3.831), stdev = 0.060
  CI (99.9%): [2.678, 4.861] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.365 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.008 ms/op
Iteration   1: 3.217 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  17.811 ms/op
                 createUser·p0.9999: 20.973 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   2: 3.257 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  10.748 ms/op
                 createUser·p0.9999: 20.316 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  13.360 ms/op
                 createUser·p0.9999: 19.103 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297932
  mean =      3.219 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23169 
    [ 2.500,  5.000) = 268711 
    [ 5.000,  7.500) = 5229 
    [ 7.500, 10.000) = 284 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 173 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     16.009 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.971 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.454 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
Iteration   1: 3.138 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.031 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   5.254 ms/op
                 existUser·p0.999:  9.847 ms/op
                 existUser·p0.9999: 20.494 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.194 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  13.825 ms/op
                 existUser·p0.9999: 22.511 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   3: 3.152 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.507 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.663 ms/op
                 existUser·p0.999:  12.674 ms/op
                 existUser·p0.9999: 19.689 ms/op
                 existUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303599
  mean =      3.161 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30662 
    [ 2.500,  5.000) = 266125 
    [ 5.000,  7.500) = 6105 
    [ 7.500, 10.000) = 265 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     21.779 ms/op
     p(99.9990) =     22.904 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.354 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.011 ms/op
Iteration   1: 3.153 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   5.325 ms/op
                 getUser·p0.999:  15.820 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   2: 3.159 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  11.256 ms/op
                 getUser·p0.9999: 22.213 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   3: 3.149 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.778 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  9.584 ms/op
                 getUser·p0.9999: 25.489 ms/op
                 getUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304211
  mean =      3.154 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10474 
    [ 2.500,  5.000) = 288282 
    [ 5.000,  7.500) = 4787 
    [ 7.500, 10.000) = 282 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     15.466 ms/op
     p(99.9900) =     23.579 ms/op
     p(99.9990) =     25.914 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.471 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.012 ms/op
Iteration   1: 3.737 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  15.701 ms/op
                 listUser·p0.9999: 22.666 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   2: 3.792 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.093 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 17.517 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   3: 3.789 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  12.730 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254369
  mean =      3.772 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 245429 
    [ 5.000,  7.500) = 6531 
    [ 7.500, 10.000) = 1714 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     24.261 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.942 ± 2.549  ops/ms
ClientPb.existUser                       thrpt       3  10.411 ± 6.010  ops/ms
ClientPb.getUser                         thrpt       3  10.076 ± 0.983  ops/ms
ClientPb.listUser                        thrpt       3   8.654 ± 3.392  ops/ms
ClientPb.createUser                       avgt       3   3.185 ± 1.363   ms/op
ClientPb.existUser                        avgt       3   3.044 ± 0.803   ms/op
ClientPb.getUser                          avgt       3   3.236 ± 1.798   ms/op
ClientPb.listUser                         avgt       3   3.770 ± 1.092   ms/op
ClientPb.createUser                     sample  297932   3.219 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.895           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.009           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.349           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.675           ms/op
ClientPb.existUser                      sample  303599   3.161 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.031           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.355           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.107           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.779           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.888           ms/op
ClientPb.getUser                        sample  304211   3.154 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.104           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.490           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.423           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.466           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.579           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.083           ms/op
ClientPb.listUser                       sample  254369   3.772 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.614           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.600           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.137           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.336           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.709           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.543           ms/op
