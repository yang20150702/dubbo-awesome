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
# Warmup Iteration   1: 2.740 ops/ms
# Warmup Iteration   2: 6.443 ops/ms
# Warmup Iteration   3: 9.156 ops/ms
Iteration   1: 9.972 ops/ms
Iteration   2: 9.811 ops/ms
Iteration   3: 9.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.923 ±(99.9%) 1.774 ops/ms [Average]
  (min, avg, max) = (9.811, 9.923, 9.986), stdev = 0.097
  CI (99.9%): [8.149, 11.698] (assumes normal distribution)


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
# Warmup Iteration   1: 3.563 ops/ms
# Warmup Iteration   2: 9.000 ops/ms
# Warmup Iteration   3: 9.990 ops/ms
Iteration   1: 10.344 ops/ms
Iteration   2: 10.697 ops/ms
Iteration   3: 10.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.431 ±(99.9%) 4.288 ops/ms [Average]
  (min, avg, max) = (10.252, 10.431, 10.697), stdev = 0.235
  CI (99.9%): [6.144, 14.719] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.608 ops/ms
# Warmup Iteration   2: 9.242 ops/ms
# Warmup Iteration   3: 9.666 ops/ms
Iteration   1: 10.046 ops/ms
Iteration   2: 10.283 ops/ms
Iteration   3: 9.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.013 ±(99.9%) 5.241 ops/ms [Average]
  (min, avg, max) = (9.711, 10.013, 10.283), stdev = 0.287
  CI (99.9%): [4.772, 15.255] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.344 ops/ms
# Warmup Iteration   2: 7.856 ops/ms
# Warmup Iteration   3: 8.449 ops/ms
Iteration   1: 8.714 ops/ms
Iteration   2: 8.453 ops/ms
Iteration   3: 8.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.621 ±(99.9%) 2.651 ops/ms [Average]
  (min, avg, max) = (8.453, 8.621, 8.714), stdev = 0.145
  CI (99.9%): [5.970, 11.271] (assumes normal distribution)


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
# Warmup Iteration   1: 7.283 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.004 ms/op
Iteration   1: 3.190 ±(99.9%) 0.007 ms/op
Iteration   2: 3.226 ±(99.9%) 0.007 ms/op
Iteration   3: 3.088 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.168 ±(99.9%) 1.305 ms/op [Average]
  (min, avg, max) = (3.088, 3.168, 3.226), stdev = 0.072
  CI (99.9%): [1.863, 4.474] (assumes normal distribution)


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
# Warmup Iteration   1: 7.062 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.003 ms/op
Iteration   1: 3.089 ±(99.9%) 0.006 ms/op
Iteration   2: 3.113 ±(99.9%) 0.002 ms/op
Iteration   3: 3.020 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.074 ±(99.9%) 0.879 ms/op [Average]
  (min, avg, max) = (3.020, 3.074, 3.113), stdev = 0.048
  CI (99.9%): [2.195, 3.953] (assumes normal distribution)


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
# Warmup Iteration   1: 7.329 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.007 ms/op
Iteration   1: 3.097 ±(99.9%) 0.001 ms/op
Iteration   2: 3.316 ±(99.9%) 0.006 ms/op
Iteration   3: 3.234 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.216 ±(99.9%) 2.023 ms/op [Average]
  (min, avg, max) = (3.097, 3.216, 3.316), stdev = 0.111
  CI (99.9%): [1.193, 5.239] (assumes normal distribution)


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
# Warmup Iteration   1: 9.167 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.007 ms/op
Iteration   1: 3.700 ±(99.9%) 0.006 ms/op
Iteration   2: 3.782 ±(99.9%) 0.006 ms/op
Iteration   3: 3.753 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.745 ±(99.9%) 0.763 ms/op [Average]
  (min, avg, max) = (3.700, 3.745, 3.782), stdev = 0.042
  CI (99.9%): [2.982, 4.509] (assumes normal distribution)


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
# Warmup Iteration   1: 8.102 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
Iteration   1: 3.138 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  18.516 ms/op
                 createUser·p0.9999: 20.789 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   2: 3.222 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  12.485 ms/op
                 createUser·p0.9999: 21.224 ms/op
                 createUser·p1.00:   22.348 ms/op

Iteration   3: 3.300 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  16.810 ms/op
                 createUser·p0.9999: 24.904 ms/op
                 createUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297943
  mean =      3.219 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27692 
    [ 2.500,  5.000) = 263834 
    [ 5.000,  7.500) = 5564 
    [ 7.500, 10.000) = 306 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 156 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     17.139 ms/op
     p(99.9900) =     24.616 ms/op
     p(99.9990) =     24.904 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.206 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
Iteration   1: 3.012 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.157 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  13.481 ms/op
                 existUser·p0.9999: 25.264 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  15.726 ms/op
                 existUser·p0.9999: 21.856 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   3: 3.135 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  8.572 ms/op
                 existUser·p0.9999: 21.221 ms/op
                 existUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312487
  mean =      3.069 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25732 
    [ 2.500,  5.000) = 282564 
    [ 5.000,  7.500) = 3375 
    [ 7.500, 10.000) = 350 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.473 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     14.066 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     25.588 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 8.234 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.010 ms/op
Iteration   1: 3.314 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  18.537 ms/op
                 getUser·p0.9999: 21.714 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   2: 3.162 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.570 ms/op
                 getUser·p0.99:   5.660 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 21.787 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  8.671 ms/op
                 getUser·p0.9999: 20.953 ms/op
                 getUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300624
  mean =      3.193 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8777 
    [ 2.500,  5.000) = 283246 
    [ 5.000,  7.500) = 7767 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 141 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     14.465 ms/op
     p(99.9900) =     21.494 ms/op
     p(99.9990) =     22.511 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 8.687 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.013 ms/op
Iteration   1: 3.970 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   6.210 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  14.090 ms/op
                 listUser·p0.9999: 22.730 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   2: 3.714 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.145 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.669 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 3.698 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.878 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.121 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  12.681 ms/op
                 listUser·p0.9999: 16.941 ms/op
                 listUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253213
  mean =      3.790 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 243870 
    [ 5.000,  7.500) = 7172 
    [ 7.500, 10.000) = 1313 
    [10.000, 12.500) = 407 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.459 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     13.284 ms/op
     p(99.9900) =     21.410 ms/op
     p(99.9990) =     22.997 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.923 ± 1.774  ops/ms
ClientPb.existUser                       thrpt       3  10.431 ± 4.288  ops/ms
ClientPb.getUser                         thrpt       3  10.013 ± 5.241  ops/ms
ClientPb.listUser                        thrpt       3   8.621 ± 2.651  ops/ms
ClientPb.createUser                       avgt       3   3.168 ± 1.305   ms/op
ClientPb.existUser                        avgt       3   3.074 ± 0.879   ms/op
ClientPb.getUser                          avgt       3   3.216 ± 2.023   ms/op
ClientPb.listUser                         avgt       3   3.745 ± 0.763   ms/op
ClientPb.createUser                     sample  297943   3.219 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.733           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.543           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.139           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.616           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.936           ms/op
ClientPb.existUser                      sample  312487   3.069 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.157           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.169           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.066           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.117           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.952           ms/op
ClientPb.getUser                        sample  300624   3.193 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.824           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.490           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.465           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.494           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.312           ms/op
ClientPb.listUser                       sample  253213   3.790 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.669           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.695           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.459           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.284           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.410           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.347           ms/op
