# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.110 ops/ms
# Warmup Iteration   2: 5.088 ops/ms
# Warmup Iteration   3: 8.384 ops/ms
Iteration   1: 9.372 ops/ms
Iteration   2: 9.511 ops/ms
Iteration   3: 9.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.486 ±(99.9%) 1.885 ops/ms [Average]
  (min, avg, max) = (9.372, 9.486, 9.574), stdev = 0.103
  CI (99.9%): [7.601, 11.370] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.389 ops/ms
# Warmup Iteration   2: 8.777 ops/ms
# Warmup Iteration   3: 9.487 ops/ms
Iteration   1: 9.899 ops/ms
Iteration   2: 9.652 ops/ms
Iteration   3: 9.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.792 ±(99.9%) 2.314 ops/ms [Average]
  (min, avg, max) = (9.652, 9.792, 9.899), stdev = 0.127
  CI (99.9%): [7.478, 12.106] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.344 ops/ms
# Warmup Iteration   2: 8.439 ops/ms
# Warmup Iteration   3: 9.066 ops/ms
Iteration   1: 9.498 ops/ms
Iteration   2: 9.268 ops/ms
Iteration   3: 9.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.418 ±(99.9%) 2.371 ops/ms [Average]
  (min, avg, max) = (9.268, 9.418, 9.498), stdev = 0.130
  CI (99.9%): [7.048, 11.789] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.101 ops/ms
# Warmup Iteration   2: 7.339 ops/ms
# Warmup Iteration   3: 8.029 ops/ms
Iteration   1: 7.989 ops/ms
Iteration   2: 8.177 ops/ms
Iteration   3: 8.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.161 ±(99.9%) 2.998 ops/ms [Average]
  (min, avg, max) = (7.989, 8.161, 8.317), stdev = 0.164
  CI (99.9%): [5.163, 11.159] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.748 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.006 ms/op
Iteration   1: 3.476 ±(99.9%) 0.009 ms/op
Iteration   2: 3.271 ±(99.9%) 0.011 ms/op
Iteration   3: 3.339 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.362 ±(99.9%) 1.907 ms/op [Average]
  (min, avg, max) = (3.271, 3.362, 3.476), stdev = 0.105
  CI (99.9%): [1.455, 5.269] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.265 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.004 ms/op
Iteration   1: 3.338 ±(99.9%) 0.003 ms/op
Iteration   2: 3.288 ±(99.9%) 0.006 ms/op
Iteration   3: 3.207 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.278 ±(99.9%) 1.212 ms/op [Average]
  (min, avg, max) = (3.207, 3.278, 3.338), stdev = 0.066
  CI (99.9%): [2.065, 4.490] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.782 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.005 ms/op
Iteration   1: 3.445 ±(99.9%) 0.006 ms/op
Iteration   2: 3.437 ±(99.9%) 0.007 ms/op
Iteration   3: 3.440 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.441 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (3.437, 3.441, 3.445), stdev = 0.004
  CI (99.9%): [3.367, 3.515] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.407 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.406 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.010 ms/op
Iteration   1: 3.906 ±(99.9%) 0.010 ms/op
Iteration   2: 3.762 ±(99.9%) 0.018 ms/op
Iteration   3: 3.922 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.863 ±(99.9%) 1.603 ms/op [Average]
  (min, avg, max) = (3.762, 3.863, 3.922), stdev = 0.088
  CI (99.9%): [2.260, 5.467] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.183 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.011 ms/op
Iteration   1: 3.422 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  20.146 ms/op
                 createUser·p0.9999: 22.652 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 3.259 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.602 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.063 ms/op
                 createUser·p0.999:  9.929 ms/op
                 createUser·p0.9999: 25.977 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   3: 3.341 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.378 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  19.863 ms/op
                 createUser·p0.9999: 25.737 ms/op
                 createUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287506
  mean =      3.339 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8568 
    [ 2.500,  5.000) = 274571 
    [ 5.000,  7.500) = 3498 
    [ 7.500, 10.000) = 449 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     19.874 ms/op
     p(99.9900) =     25.502 ms/op
     p(99.9990) =     26.550 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.267 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.009 ms/op
Iteration   1: 3.200 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  10.452 ms/op
                 existUser·p0.9999: 22.839 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   2: 3.357 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  20.254 ms/op
                 existUser·p0.9999: 25.133 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   3: 3.282 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.364 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   4.045 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  13.467 ms/op
                 existUser·p0.9999: 25.502 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292869
  mean =      3.278 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10684 
    [ 2.500,  5.000) = 277118 
    [ 5.000,  7.500) = 3968 
    [ 7.500, 10.000) = 596 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.364 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     24.852 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.390 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.011 ms/op
Iteration   1: 3.455 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  21.052 ms/op
                 getUser·p0.9999: 24.805 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   2: 3.445 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.668 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  10.934 ms/op
                 getUser·p0.9999: 24.554 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.515 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.125 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  19.266 ms/op
                 getUser·p0.9999: 26.932 ms/op
                 getUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276415
  mean =      3.471 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13452 
    [ 2.500,  5.000) = 253236 
    [ 5.000,  7.500) = 8508 
    [ 7.500, 10.000) = 841 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     11.534 ms/op
     p(99.9900) =     25.964 ms/op
     p(99.9990) =     27.074 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.644 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.126 ±(99.9%) 0.014 ms/op
Iteration   1: 4.035 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.886 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  19.503 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 4.059 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.956 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  14.195 ms/op
                 listUser·p0.9999: 15.581 ms/op
                 listUser·p1.00:   16.122 ms/op

Iteration   3: 3.921 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.867 ms/op
                 listUser·p0.9999: 16.155 ms/op
                 listUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239761
  mean =      4.004 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 230448 
    [ 5.000,  7.500) = 7137 
    [ 7.500, 10.000) = 1248 
    [10.000, 12.500) = 391 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     15.090 ms/op
     p(99.9900) =     22.414 ms/op
     p(99.9990) =     23.908 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.486 ± 1.885  ops/ms
ClientPb.existUser                       thrpt       3   9.792 ± 2.314  ops/ms
ClientPb.getUser                         thrpt       3   9.418 ± 2.371  ops/ms
ClientPb.listUser                        thrpt       3   8.161 ± 2.998  ops/ms
ClientPb.createUser                       avgt       3   3.362 ± 1.907   ms/op
ClientPb.existUser                        avgt       3   3.278 ± 1.212   ms/op
ClientPb.getUser                          avgt       3   3.441 ± 0.074   ms/op
ClientPb.listUser                         avgt       3   3.863 ± 1.603   ms/op
ClientPb.createUser                     sample  287506   3.339 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.378           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.874           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.502           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.968           ms/op
ClientPb.existUser                      sample  292869   3.278 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.364           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.402           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.852           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.575           ms/op
ClientPb.getUser                        sample  276415   3.471 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.668           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.534           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.964           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.165           ms/op
ClientPb.listUser                       sample  239761   4.004 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.325           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.090           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.414           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.150           ms/op
