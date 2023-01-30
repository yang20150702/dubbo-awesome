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
# Warmup Iteration   1: 2.048 ops/ms
# Warmup Iteration   2: 5.448 ops/ms
# Warmup Iteration   3: 8.565 ops/ms
Iteration   1: 8.905 ops/ms
Iteration   2: 9.056 ops/ms
Iteration   3: 9.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.121 ±(99.9%) 4.670 ops/ms [Average]
  (min, avg, max) = (8.905, 9.121, 9.404), stdev = 0.256
  CI (99.9%): [4.452, 13.791] (assumes normal distribution)


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
# Warmup Iteration   1: 2.913 ops/ms
# Warmup Iteration   2: 8.466 ops/ms
# Warmup Iteration   3: 9.175 ops/ms
Iteration   1: 9.647 ops/ms
Iteration   2: 9.697 ops/ms
Iteration   3: 9.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.616 ±(99.9%) 1.815 ops/ms [Average]
  (min, avg, max) = (9.505, 9.616, 9.697), stdev = 0.099
  CI (99.9%): [7.801, 11.431] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.667 ops/ms
# Warmup Iteration   2: 8.112 ops/ms
# Warmup Iteration   3: 8.981 ops/ms
Iteration   1: 8.959 ops/ms
Iteration   2: 9.563 ops/ms
Iteration   3: 9.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.300 ±(99.9%) 5.646 ops/ms [Average]
  (min, avg, max) = (8.959, 9.300, 9.563), stdev = 0.309
  CI (99.9%): [3.654, 14.946] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.777 ops/ms
# Warmup Iteration   2: 7.158 ops/ms
# Warmup Iteration   3: 7.662 ops/ms
Iteration   1: 7.882 ops/ms
Iteration   2: 7.907 ops/ms
Iteration   3: 8.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.938 ±(99.9%) 1.397 ops/ms [Average]
  (min, avg, max) = (7.882, 7.938, 8.026), stdev = 0.077
  CI (99.9%): [6.541, 9.336] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.815 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.621 ±(99.9%) 0.006 ms/op
Iteration   1: 3.401 ±(99.9%) 0.008 ms/op
Iteration   2: 3.363 ±(99.9%) 0.007 ms/op
Iteration   3: 3.469 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.411 ±(99.9%) 0.976 ms/op [Average]
  (min, avg, max) = (3.363, 3.411, 3.469), stdev = 0.053
  CI (99.9%): [2.435, 4.386] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.288 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.005 ms/op
Iteration   1: 3.437 ±(99.9%) 0.006 ms/op
Iteration   2: 3.388 ±(99.9%) 0.009 ms/op
Iteration   3: 3.378 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.401 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (3.378, 3.401, 3.437), stdev = 0.032
  CI (99.9%): [2.819, 3.983] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 8.974 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.006 ms/op
Iteration   1: 3.424 ±(99.9%) 0.004 ms/op
Iteration   2: 3.434 ±(99.9%) 0.009 ms/op
Iteration   3: 3.304 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.387 ±(99.9%) 1.324 ms/op [Average]
  (min, avg, max) = (3.304, 3.387, 3.434), stdev = 0.073
  CI (99.9%): [2.063, 4.711] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 11.856 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.489 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.192 ±(99.9%) 0.010 ms/op
Iteration   1: 4.019 ±(99.9%) 0.009 ms/op
Iteration   2: 3.982 ±(99.9%) 0.013 ms/op
Iteration   3: 3.927 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.976 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (3.927, 3.976, 4.019), stdev = 0.046
  CI (99.9%): [3.131, 4.820] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.248 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.010 ms/op
Iteration   1: 3.740 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.988 ms/op
                 createUser·p0.99:   7.512 ms/op
                 createUser·p0.999:  22.151 ms/op
                 createUser·p0.9999: 24.867 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   2: 3.560 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  24.428 ms/op
                 createUser·p0.9999: 30.639 ms/op
                 createUser·p1.00:   31.425 ms/op

Iteration   3: 3.646 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.480 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  25.095 ms/op
                 createUser·p0.9999: 35.717 ms/op
                 createUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 263161
  mean =      3.647 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3845 
    [ 2.500,  5.000) = 247303 
    [ 5.000,  7.500) = 10383 
    [ 7.500, 10.000) = 1101 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.480 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     22.572 ms/op
     p(99.9900) =     34.455 ms/op
     p(99.9990) =     35.979 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.980 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.008 ms/op
Iteration   1: 3.459 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.655 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  19.792 ms/op
                 existUser·p0.9999: 23.339 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   2: 3.475 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  21.627 ms/op
                 existUser·p0.9999: 23.914 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   3: 3.401 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.109 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  10.256 ms/op
                 existUser·p0.9999: 28.770 ms/op
                 existUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278576
  mean =      3.445 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8898 
    [ 2.500,  5.000) = 263341 
    [ 5.000,  7.500) = 5156 
    [ 7.500, 10.000) = 834 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     13.438 ms/op
     p(99.9900) =     27.038 ms/op
     p(99.9990) =     29.152 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 10.707 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.010 ms/op
Iteration   1: 3.698 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  21.767 ms/op
                 getUser·p0.9999: 23.736 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   2: 3.393 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  22.772 ms/op
                 getUser·p0.9999: 32.000 ms/op
                 getUser·p1.00:   34.996 ms/op

Iteration   3: 3.461 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  22.108 ms/op
                 getUser·p0.9999: 26.797 ms/op
                 getUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273035
  mean =      3.512 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5746 
    [ 2.500,  5.000) = 258478 
    [ 5.000,  7.500) = 7492 
    [ 7.500, 10.000) = 814 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     21.822 ms/op
     p(99.9900) =     30.399 ms/op
     p(99.9990) =     32.734 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 10.278 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.491 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.245 ±(99.9%) 0.013 ms/op
Iteration   1: 4.205 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 28.279 ms/op
                 listUser·p1.00:   29.590 ms/op

Iteration   2: 4.058 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 25.923 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   3: 3.999 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 23.036 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234986
  mean =      4.085 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 226149 
    [ 5.000,  7.500) = 6081 
    [ 7.500, 10.000) = 1809 
    [10.000, 12.500) = 381 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     16.499 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     29.349 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.121 ± 4.670  ops/ms
ClientPb.existUser                       thrpt       3   9.616 ± 1.815  ops/ms
ClientPb.getUser                         thrpt       3   9.300 ± 5.646  ops/ms
ClientPb.listUser                        thrpt       3   7.938 ± 1.397  ops/ms
ClientPb.createUser                       avgt       3   3.411 ± 0.976   ms/op
ClientPb.existUser                        avgt       3   3.401 ± 0.582   ms/op
ClientPb.getUser                          avgt       3   3.387 ± 1.324   ms/op
ClientPb.listUser                         avgt       3   3.976 ± 0.844   ms/op
ClientPb.createUser                     sample  263161   3.647 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.480           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.461           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.825           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.102           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.572           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.455           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.110           ms/op
ClientPb.existUser                      sample  278576   3.445 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.984           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.988           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.438           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.038           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.393           ms/op
ClientPb.getUser                        sample  273035   3.512 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.075           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.644           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.822           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.399           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.996           ms/op
ClientPb.listUser                       sample  234986   4.085 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.710           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.766           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.499           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.132           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.590           ms/op
