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
# Warmup Iteration   1: 1.743 ops/ms
# Warmup Iteration   2: 4.522 ops/ms
# Warmup Iteration   3: 8.256 ops/ms
Iteration   1: 8.713 ops/ms
Iteration   2: 9.039 ops/ms
Iteration   3: 9.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.008 ±(99.9%) 5.119 ops/ms [Average]
  (min, avg, max) = (8.713, 9.008, 9.271), stdev = 0.281
  CI (99.9%): [3.889, 14.127] (assumes normal distribution)


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
# Warmup Iteration   1: 2.762 ops/ms
# Warmup Iteration   2: 8.353 ops/ms
# Warmup Iteration   3: 9.125 ops/ms
Iteration   1: 9.266 ops/ms
Iteration   2: 9.716 ops/ms
Iteration   3: 9.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.383 ±(99.9%) 5.352 ops/ms [Average]
  (min, avg, max) = (9.166, 9.383, 9.716), stdev = 0.293
  CI (99.9%): [4.031, 14.735] (assumes normal distribution)


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
# Warmup Iteration   1: 2.689 ops/ms
# Warmup Iteration   2: 7.458 ops/ms
# Warmup Iteration   3: 8.570 ops/ms
Iteration   1: 9.081 ops/ms
Iteration   2: 8.625 ops/ms
Iteration   3: 8.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.900 ±(99.9%) 4.411 ops/ms [Average]
  (min, avg, max) = (8.625, 8.900, 9.081), stdev = 0.242
  CI (99.9%): [4.489, 13.311] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.512 ops/ms
# Warmup Iteration   2: 6.945 ops/ms
# Warmup Iteration   3: 7.600 ops/ms
Iteration   1: 7.527 ops/ms
Iteration   2: 7.983 ops/ms
Iteration   3: 7.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.804 ±(99.9%) 4.431 ops/ms [Average]
  (min, avg, max) = (7.527, 7.804, 7.983), stdev = 0.243
  CI (99.9%): [3.373, 12.234] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.874 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.008 ms/op
Iteration   1: 3.628 ±(99.9%) 0.010 ms/op
Iteration   2: 3.576 ±(99.9%) 0.007 ms/op
Iteration   3: 3.435 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.546 ±(99.9%) 1.820 ms/op [Average]
  (min, avg, max) = (3.435, 3.546, 3.628), stdev = 0.100
  CI (99.9%): [1.726, 5.366] (assumes normal distribution)


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
# Warmup Iteration   1: 9.064 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.005 ms/op
Iteration   1: 3.331 ±(99.9%) 0.009 ms/op
Iteration   2: 3.298 ±(99.9%) 0.009 ms/op
Iteration   3: 3.361 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.330 ±(99.9%) 0.575 ms/op [Average]
  (min, avg, max) = (3.298, 3.330, 3.361), stdev = 0.032
  CI (99.9%): [2.755, 3.905] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.776 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.029 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.004 ms/op
Iteration   1: 3.514 ±(99.9%) 0.005 ms/op
Iteration   2: 3.602 ±(99.9%) 0.006 ms/op
Iteration   3: 3.535 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.550 ±(99.9%) 0.841 ms/op [Average]
  (min, avg, max) = (3.514, 3.550, 3.602), stdev = 0.046
  CI (99.9%): [2.709, 4.391] (assumes normal distribution)


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
# Warmup Iteration   1: 11.263 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.677 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.357 ±(99.9%) 0.006 ms/op
Iteration   1: 4.242 ±(99.9%) 0.009 ms/op
Iteration   2: 4.084 ±(99.9%) 0.015 ms/op
Iteration   3: 4.054 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.127 ±(99.9%) 1.838 ms/op [Average]
  (min, avg, max) = (4.054, 4.127, 4.242), stdev = 0.101
  CI (99.9%): [2.289, 5.965] (assumes normal distribution)


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
# Warmup Iteration   1: 10.939 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.015 ms/op
Iteration   1: 3.556 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  11.273 ms/op
                 createUser·p0.9999: 24.939 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 3.480 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  21.875 ms/op
                 createUser·p0.9999: 25.225 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   3: 3.395 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  24.264 ms/op
                 createUser·p0.9999: 29.674 ms/op
                 createUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276008
  mean =      3.476 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4343 
    [ 2.500,  5.000) = 265335 
    [ 5.000,  7.500) = 5363 
    [ 7.500, 10.000) = 532 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 151 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     27.918 ms/op
     p(99.9990) =     30.318 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 9.468 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.011 ms/op
Iteration   1: 3.327 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.415 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  18.268 ms/op
                 existUser·p0.9999: 23.507 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   2: 3.347 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  11.796 ms/op
                 existUser·p0.9999: 25.214 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   3: 3.359 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.653 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  25.269 ms/op
                 existUser·p0.9999: 35.421 ms/op
                 existUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286792
  mean =      3.345 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7294 
    [ 2.500,  5.000) = 274786 
    [ 5.000,  7.500) = 3811 
    [ 7.500, 10.000) = 567 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     11.846 ms/op
     p(99.9900) =     34.341 ms/op
     p(99.9990) =     35.595 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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
# Warmup Iteration   1: 9.913 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.012 ms/op
Iteration   1: 3.740 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  20.349 ms/op
                 getUser·p0.9999: 22.836 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 3.446 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.679 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  22.806 ms/op
                 getUser·p0.9999: 31.612 ms/op
                 getUser·p1.00:   31.916 ms/op

Iteration   3: 3.478 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.679 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  19.207 ms/op
                 getUser·p0.9999: 31.189 ms/op
                 getUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270137
  mean =      3.550 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2077 
    [ 2.500,  5.000) = 260725 
    [ 5.000,  7.500) = 5794 
    [ 7.500, 10.000) = 1035 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     31.195 ms/op
     p(99.9990) =     32.286 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 11.521 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.577 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.175 ±(99.9%) 0.013 ms/op
Iteration   1: 4.120 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.812 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.668 ms/op
                 listUser·p0.999:  20.818 ms/op
                 listUser·p0.9999: 26.947 ms/op
                 listUser·p1.00:   32.342 ms/op

Iteration   2: 4.091 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   8.036 ms/op
                 listUser·p0.999:  15.138 ms/op
                 listUser·p0.9999: 18.165 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 3.989 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.246 ms/op
                 listUser·p0.9999: 21.821 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235946
  mean =      4.066 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 227415 
    [ 5.000,  7.500) = 6182 
    [ 7.500, 10.000) = 1517 
    [10.000, 12.500) = 301 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.812 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     15.828 ms/op
     p(99.9900) =     23.967 ms/op
     p(99.9990) =     31.860 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.008 ± 5.119  ops/ms
ClientPb.existUser                       thrpt       3   9.383 ± 5.352  ops/ms
ClientPb.getUser                         thrpt       3   8.900 ± 4.411  ops/ms
ClientPb.listUser                        thrpt       3   7.804 ± 4.431  ops/ms
ClientPb.createUser                       avgt       3   3.546 ± 1.820   ms/op
ClientPb.existUser                        avgt       3   3.330 ± 0.575   ms/op
ClientPb.getUser                          avgt       3   3.550 ± 0.841   ms/op
ClientPb.listUser                         avgt       3   4.127 ± 1.838   ms/op
ClientPb.createUser                     sample  276008   3.476 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.192           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.988           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.742           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.918           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.376           ms/op
ClientPb.existUser                      sample  286792   3.345 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.190           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.936           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.693           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.846           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.341           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.717           ms/op
ClientPb.getUser                        sample  270137   3.550 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.143           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.726           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.054           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.195           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.309           ms/op
ClientPb.listUser                       sample  235946   4.066 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.812           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.828           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.967           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.342           ms/op
