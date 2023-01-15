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
# Warmup Iteration   1: 2.210 ops/ms
# Warmup Iteration   2: 6.118 ops/ms
# Warmup Iteration   3: 8.825 ops/ms
Iteration   1: 9.627 ops/ms
Iteration   2: 9.581 ops/ms
Iteration   3: 9.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.512 ±(99.9%) 2.940 ops/ms [Average]
  (min, avg, max) = (9.328, 9.512, 9.627), stdev = 0.161
  CI (99.9%): [6.572, 12.452] (assumes normal distribution)


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
# Warmup Iteration   1: 2.916 ops/ms
# Warmup Iteration   2: 8.139 ops/ms
# Warmup Iteration   3: 9.537 ops/ms
Iteration   1: 9.821 ops/ms
Iteration   2: 9.889 ops/ms
Iteration   3: 9.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.721 ±(99.9%) 4.298 ops/ms [Average]
  (min, avg, max) = (9.452, 9.721, 9.889), stdev = 0.236
  CI (99.9%): [5.423, 14.019] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.626 ops/ms
# Warmup Iteration   2: 8.441 ops/ms
# Warmup Iteration   3: 8.959 ops/ms
Iteration   1: 9.419 ops/ms
Iteration   2: 9.526 ops/ms
Iteration   3: 9.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.385 ±(99.9%) 2.957 ops/ms [Average]
  (min, avg, max) = (9.208, 9.385, 9.526), stdev = 0.162
  CI (99.9%): [6.428, 12.341] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.807 ops/ms
# Warmup Iteration   2: 7.380 ops/ms
# Warmup Iteration   3: 7.747 ops/ms
Iteration   1: 8.000 ops/ms
Iteration   2: 8.119 ops/ms
Iteration   3: 8.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.140 ±(99.9%) 2.752 ops/ms [Average]
  (min, avg, max) = (8.000, 8.140, 8.300), stdev = 0.151
  CI (99.9%): [5.388, 10.891] (assumes normal distribution)


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
# Warmup Iteration   1: 10.110 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.004 ms/op
Iteration   1: 3.330 ±(99.9%) 0.008 ms/op
Iteration   2: 3.401 ±(99.9%) 0.009 ms/op
Iteration   3: 3.497 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.410 ±(99.9%) 1.531 ms/op [Average]
  (min, avg, max) = (3.330, 3.410, 3.497), stdev = 0.084
  CI (99.9%): [1.879, 4.940] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.028 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.005 ms/op
Iteration   1: 3.138 ±(99.9%) 0.008 ms/op
Iteration   2: 3.239 ±(99.9%) 0.010 ms/op
Iteration   3: 3.201 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.193 ±(99.9%) 0.929 ms/op [Average]
  (min, avg, max) = (3.138, 3.193, 3.239), stdev = 0.051
  CI (99.9%): [2.264, 4.122] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.941 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.009 ms/op
Iteration   1: 3.307 ±(99.9%) 0.010 ms/op
Iteration   2: 3.238 ±(99.9%) 0.006 ms/op
Iteration   3: 3.318 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.287 ±(99.9%) 0.791 ms/op [Average]
  (min, avg, max) = (3.238, 3.287, 3.318), stdev = 0.043
  CI (99.9%): [2.496, 4.079] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.377 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.014 ms/op
Iteration   1: 3.889 ±(99.9%) 0.012 ms/op
Iteration   2: 3.843 ±(99.9%) 0.011 ms/op
Iteration   3: 3.894 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.875 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (3.843, 3.875, 3.894), stdev = 0.028
  CI (99.9%): [3.366, 4.385] (assumes normal distribution)


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
# Warmup Iteration   1: 10.562 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.647 ±(99.9%) 0.012 ms/op
Iteration   1: 3.292 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  13.266 ms/op
                 createUser·p0.9999: 23.667 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   2: 3.324 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.894 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.027 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  20.321 ms/op
                 createUser·p0.9999: 25.236 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 3.285 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.548 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.523 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  16.166 ms/op
                 createUser·p0.9999: 23.929 ms/op
                 createUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290843
  mean =      3.300 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17688 
    [ 2.500,  5.000) = 269081 
    [ 5.000,  7.500) = 3136 
    [ 7.500, 10.000) = 464 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     16.030 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     25.708 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 8.509 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.007 ms/op
Iteration   1: 3.280 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 23.863 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   2: 3.299 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  10.987 ms/op
                 existUser·p0.9999: 25.466 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   3: 3.264 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  9.277 ms/op
                 existUser·p0.9999: 25.507 ms/op
                 existUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292590
  mean =      3.281 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16418 
    [ 2.500,  5.000) = 270501 
    [ 5.000,  7.500) = 4932 
    [ 7.500, 10.000) = 433 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 205 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     10.355 ms/op
     p(99.9900) =     25.157 ms/op
     p(99.9990) =     26.446 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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
# Warmup Iteration   1: 9.044 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.687 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.012 ms/op
Iteration   1: 3.450 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  14.547 ms/op
                 getUser·p0.9999: 22.820 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   2: 3.368 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  21.346 ms/op
                 getUser·p0.9999: 32.262 ms/op
                 getUser·p1.00:   33.423 ms/op

Iteration   3: 3.352 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  21.478 ms/op
                 getUser·p0.9999: 29.058 ms/op
                 getUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283250
  mean =      3.390 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13967 
    [ 2.500,  5.000) = 261870 
    [ 5.000,  7.500) = 6095 
    [ 7.500, 10.000) = 860 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     16.036 ms/op
     p(99.9900) =     30.694 ms/op
     p(99.9990) =     32.976 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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
# Warmup Iteration   1: 11.041 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.536 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.249 ±(99.9%) 0.014 ms/op
Iteration   1: 4.056 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  23.497 ms/op
                 listUser·p0.9999: 30.048 ms/op
                 listUser·p1.00:   33.456 ms/op

Iteration   2: 3.980 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.880 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.694 ms/op
                 listUser·p0.9999: 25.264 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   3: 3.893 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  17.727 ms/op
                 listUser·p0.9999: 30.643 ms/op
                 listUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241395
  mean =      3.975 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 233856 
    [ 5.000,  7.500) = 5425 
    [ 7.500, 10.000) = 1286 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     18.173 ms/op
     p(99.9900) =     29.978 ms/op
     p(99.9990) =     33.226 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.512 ± 2.940  ops/ms
ClientPb.existUser                       thrpt       3   9.721 ± 4.298  ops/ms
ClientPb.getUser                         thrpt       3   9.385 ± 2.957  ops/ms
ClientPb.listUser                        thrpt       3   8.140 ± 2.752  ops/ms
ClientPb.createUser                       avgt       3   3.410 ± 1.531   ms/op
ClientPb.existUser                        avgt       3   3.193 ± 0.929   ms/op
ClientPb.getUser                          avgt       3   3.287 ± 0.791   ms/op
ClientPb.listUser                         avgt       3   3.875 ± 0.510   ms/op
ClientPb.createUser                     sample  290843   3.300 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.423           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.551           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.030           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.281           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.378           ms/op
ClientPb.existUser                      sample  292590   3.281 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.015           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.994           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.355           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.157           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.771           ms/op
ClientPb.getUser                        sample  283250   3.390 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.769           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.186           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.036           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.694           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.423           ms/op
ClientPb.listUser                       sample  241395   3.975 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.413           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.176           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.173           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.978           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.456           ms/op
