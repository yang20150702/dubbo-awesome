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
# Warmup Iteration   1: 2.275 ops/ms
# Warmup Iteration   2: 5.918 ops/ms
# Warmup Iteration   3: 9.146 ops/ms
Iteration   1: 9.460 ops/ms
Iteration   2: 9.660 ops/ms
Iteration   3: 10.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.770 ±(99.9%) 6.883 ops/ms [Average]
  (min, avg, max) = (9.460, 9.770, 10.190), stdev = 0.377
  CI (99.9%): [2.887, 16.653] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.283 ops/ms
# Warmup Iteration   2: 8.998 ops/ms
# Warmup Iteration   3: 10.113 ops/ms
Iteration   1: 10.145 ops/ms
Iteration   2: 10.288 ops/ms
Iteration   3: 10.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.162 ±(99.9%) 2.155 ops/ms [Average]
  (min, avg, max) = (10.054, 10.162, 10.288), stdev = 0.118
  CI (99.9%): [8.008, 12.317] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.568 ops/ms
# Warmup Iteration   2: 8.925 ops/ms
# Warmup Iteration   3: 9.718 ops/ms
Iteration   1: 10.108 ops/ms
Iteration   2: 10.068 ops/ms
Iteration   3: 10.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.064 ±(99.9%) 0.861 ops/ms [Average]
  (min, avg, max) = (10.014, 10.064, 10.108), stdev = 0.047
  CI (99.9%): [9.202, 10.925] (assumes normal distribution)


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
# Warmup Iteration   1: 3.174 ops/ms
# Warmup Iteration   2: 7.417 ops/ms
# Warmup Iteration   3: 8.365 ops/ms
Iteration   1: 8.522 ops/ms
Iteration   2: 8.331 ops/ms
Iteration   3: 8.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.289 ±(99.9%) 4.679 ops/ms [Average]
  (min, avg, max) = (8.014, 8.289, 8.522), stdev = 0.256
  CI (99.9%): [3.609, 12.968] (assumes normal distribution)


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
# Warmup Iteration   1: 7.114 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.001 ms/op
Iteration   1: 3.329 ±(99.9%) 0.009 ms/op
Iteration   2: 3.255 ±(99.9%) 0.003 ms/op
Iteration   3: 3.156 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.247 ±(99.9%) 1.584 ms/op [Average]
  (min, avg, max) = (3.156, 3.247, 3.329), stdev = 0.087
  CI (99.9%): [1.663, 4.831] (assumes normal distribution)


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
# Warmup Iteration   1: 8.668 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.433 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.004 ms/op
Iteration   1: 3.146 ±(99.9%) 0.006 ms/op
Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
Iteration   3: 3.037 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.090 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (3.037, 3.090, 3.146), stdev = 0.055
  CI (99.9%): [2.095, 4.086] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.833 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.005 ms/op
Iteration   1: 3.318 ±(99.9%) 0.002 ms/op
Iteration   2: 3.223 ±(99.9%) 0.008 ms/op
Iteration   3: 3.131 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.224 ±(99.9%) 1.709 ms/op [Average]
  (min, avg, max) = (3.131, 3.224, 3.318), stdev = 0.094
  CI (99.9%): [1.515, 4.933] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.143 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.005 ms/op
Iteration   1: 3.831 ±(99.9%) 0.008 ms/op
Iteration   2: 3.774 ±(99.9%) 0.008 ms/op
Iteration   3: 3.744 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.783 ±(99.9%) 0.808 ms/op [Average]
  (min, avg, max) = (3.744, 3.783, 3.831), stdev = 0.044
  CI (99.9%): [2.975, 4.591] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.757 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.745 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.008 ms/op
Iteration   1: 3.370 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.776 ms/op
                 createUser·p0.999:  18.434 ms/op
                 createUser·p0.9999: 24.019 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   2: 3.182 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.511 ms/op
                 createUser·p0.999:  20.564 ms/op
                 createUser·p0.9999: 25.683 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.199 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.907 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  16.312 ms/op
                 createUser·p0.9999: 24.609 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295120
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13501 
    [ 2.500,  5.000) = 274247 
    [ 5.000,  7.500) = 6349 
    [ 7.500, 10.000) = 642 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     24.821 ms/op
     p(99.9990) =     25.828 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.234 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.008 ms/op
Iteration   1: 3.181 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  8.886 ms/op
                 existUser·p0.9999: 24.576 ms/op
                 existUser·p1.00:   24.969 ms/op

Iteration   2: 3.075 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  13.533 ms/op
                 existUser·p0.9999: 21.876 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   3: 3.096 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.464 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  10.343 ms/op
                 existUser·p0.9999: 23.757 ms/op
                 existUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308012
  mean =      3.117 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14191 
    [ 2.500,  5.000) = 289831 
    [ 5.000,  7.500) = 3289 
    [ 7.500, 10.000) = 280 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     23.829 ms/op
     p(99.9990) =     24.901 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 8.010 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.009 ms/op
Iteration   1: 3.425 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.664 ms/op
                 getUser·p0.999:  16.244 ms/op
                 getUser·p0.9999: 18.809 ms/op
                 getUser·p1.00:   19.399 ms/op

Iteration   2: 3.211 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  10.568 ms/op
                 getUser·p0.9999: 21.464 ms/op
                 getUser·p1.00:   22.446 ms/op

Iteration   3: 3.338 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.265 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  16.862 ms/op
                 getUser·p0.9999: 27.061 ms/op
                 getUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288959
  mean =      3.322 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25811 
    [ 2.500,  5.000) = 255116 
    [ 5.000,  7.500) = 7044 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     26.231 ms/op
     p(99.9990) =     27.489 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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
# Warmup Iteration   1: 9.073 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.012 ms/op
Iteration   1: 3.807 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  18.186 ms/op
                 listUser·p0.9999: 20.532 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   2: 3.724 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 20.133 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   3: 3.791 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 21.383 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254127
  mean =      3.774 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 247143 
    [ 5.000,  7.500) = 5126 
    [ 7.500, 10.000) = 1014 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 359 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.627 ms/op
     p(99.9900) =     20.663 ms/op
     p(99.9990) =     21.807 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.770 ± 6.883  ops/ms
ClientPb.existUser                       thrpt       3  10.162 ± 2.155  ops/ms
ClientPb.getUser                         thrpt       3  10.064 ± 0.861  ops/ms
ClientPb.listUser                        thrpt       3   8.289 ± 4.679  ops/ms
ClientPb.createUser                       avgt       3   3.247 ± 1.584   ms/op
ClientPb.existUser                        avgt       3   3.090 ± 0.996   ms/op
ClientPb.getUser                          avgt       3   3.224 ± 1.709   ms/op
ClientPb.listUser                         avgt       3   3.783 ± 0.808   ms/op
ClientPb.createUser                     sample  295120   3.248 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.149           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.628           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.007           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.821           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.214           ms/op
ClientPb.existUser                      sample  308012   3.117 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.317           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.226           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.517           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.829           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.969           ms/op
ClientPb.getUser                        sample  288959   3.322 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.740           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.956           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.073           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.231           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.853           ms/op
ClientPb.listUser                       sample  254127   3.774 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.194           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.840           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.627           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.663           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.053           ms/op
