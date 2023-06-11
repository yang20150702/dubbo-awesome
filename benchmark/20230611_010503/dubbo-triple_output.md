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
# Warmup Iteration   1: 1.380 ops/ms
# Warmup Iteration   2: 3.466 ops/ms
# Warmup Iteration   3: 6.136 ops/ms
Iteration   1: 6.568 ops/ms
Iteration   2: 6.627 ops/ms
Iteration   3: 6.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.712 ±(99.9%) 3.663 ops/ms [Average]
  (min, avg, max) = (6.568, 6.712, 6.941), stdev = 0.201
  CI (99.9%): [3.049, 10.375] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.869 ops/ms
# Warmup Iteration   2: 5.268 ops/ms
# Warmup Iteration   3: 7.150 ops/ms
Iteration   1: 7.292 ops/ms
Iteration   2: 6.971 ops/ms
Iteration   3: 6.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.000 ±(99.9%) 5.097 ops/ms [Average]
  (min, avg, max) = (6.736, 7.000, 7.292), stdev = 0.279
  CI (99.9%): [1.903, 12.097] (assumes normal distribution)


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
# Warmup Iteration   1: 2.007 ops/ms
# Warmup Iteration   2: 5.990 ops/ms
# Warmup Iteration   3: 6.896 ops/ms
Iteration   1: 7.232 ops/ms
Iteration   2: 7.675 ops/ms
Iteration   3: 7.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.493 ±(99.9%) 4.234 ops/ms [Average]
  (min, avg, max) = (7.232, 7.493, 7.675), stdev = 0.232
  CI (99.9%): [3.260, 11.727] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.028 ops/ms
# Warmup Iteration   2: 5.082 ops/ms
# Warmup Iteration   3: 5.678 ops/ms
Iteration   1: 6.068 ops/ms
Iteration   2: 6.661 ops/ms
Iteration   3: 6.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.282 ±(99.9%) 6.002 ops/ms [Average]
  (min, avg, max) = (6.068, 6.282, 6.661), stdev = 0.329
  CI (99.9%): [0.280, 12.283] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.707 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.778 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.870 ±(99.9%) 0.007 ms/op
Iteration   1: 4.369 ±(99.9%) 0.013 ms/op
Iteration   2: 4.256 ±(99.9%) 0.014 ms/op
Iteration   3: 4.165 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.263 ±(99.9%) 1.868 ms/op [Average]
  (min, avg, max) = (4.165, 4.263, 4.369), stdev = 0.102
  CI (99.9%): [2.396, 6.131] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.692 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.606 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.012 ms/op
Iteration   1: 4.238 ±(99.9%) 0.018 ms/op
Iteration   2: 4.197 ±(99.9%) 0.010 ms/op
Iteration   3: 4.089 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.175 ±(99.9%) 1.407 ms/op [Average]
  (min, avg, max) = (4.089, 4.175, 4.238), stdev = 0.077
  CI (99.9%): [2.768, 5.582] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.645 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.142 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.538 ±(99.9%) 0.012 ms/op
Iteration   1: 4.484 ±(99.9%) 0.008 ms/op
Iteration   2: 4.429 ±(99.9%) 0.010 ms/op
Iteration   3: 4.623 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.512 ±(99.9%) 1.831 ms/op [Average]
  (min, avg, max) = (4.429, 4.512, 4.623), stdev = 0.100
  CI (99.9%): [2.681, 6.343] (assumes normal distribution)


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
# Warmup Iteration   1: 14.888 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 6.846 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.778 ±(99.9%) 0.016 ms/op
Iteration   1: 5.441 ±(99.9%) 0.016 ms/op
Iteration   2: 5.502 ±(99.9%) 0.012 ms/op
Iteration   3: 5.164 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.369 ±(99.9%) 3.289 ms/op [Average]
  (min, avg, max) = (5.164, 5.369, 5.502), stdev = 0.180
  CI (99.9%): [2.080, 8.658] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.123 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 5.572 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.652 ±(99.9%) 0.024 ms/op
Iteration   1: 5.226 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.109 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   6.308 ms/op
                 createUser·p0.95:   7.399 ms/op
                 createUser·p0.99:   10.457 ms/op
                 createUser·p0.999:  22.625 ms/op
                 createUser·p0.9999: 27.149 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   2: 5.395 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.642 ms/op
                 createUser·p0.50:   5.128 ms/op
                 createUser·p0.90:   6.455 ms/op
                 createUser·p0.95:   7.430 ms/op
                 createUser·p0.99:   11.158 ms/op
                 createUser·p0.999:  27.541 ms/op
                 createUser·p0.9999: 34.739 ms/op
                 createUser·p1.00:   36.176 ms/op

Iteration   3: 5.568 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.749 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   6.414 ms/op
                 createUser·p0.95:   7.447 ms/op
                 createUser·p0.99:   10.256 ms/op
                 createUser·p0.999:  30.906 ms/op
                 createUser·p0.9999: 39.470 ms/op
                 createUser·p1.00:   40.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 177855
  mean =      5.393 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 66061 
    [ 5.000, 10.000) = 109482 
    [10.000, 15.000) = 1913 
    [15.000, 20.000) = 140 
    [20.000, 25.000) = 76 
    [25.000, 30.000) = 60 
    [30.000, 35.000) = 91 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.398 ms/op
     p(95.0000) =      7.430 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     25.512 ms/op
     p(99.9900) =     38.877 ms/op
     p(99.9990) =     40.013 ms/op
     p(99.9999) =     40.370 ms/op
    p(100.0000) =     40.370 ms/op


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
# Warmup Iteration   1: 17.701 ±(99.9%) 0.327 ms/op
# Warmup Iteration   2: 7.019 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.359 ±(99.9%) 0.021 ms/op
Iteration   1: 5.034 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.204 ms/op
                 existUser·p0.50:   4.833 ms/op
                 existUser·p0.90:   6.062 ms/op
                 existUser·p0.95:   6.708 ms/op
                 existUser·p0.99:   9.322 ms/op
                 existUser·p0.999:  20.803 ms/op
                 existUser·p0.9999: 25.306 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   2: 4.705 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.021 ms/op
                 existUser·p0.50:   4.432 ms/op
                 existUser·p0.90:   5.931 ms/op
                 existUser·p0.95:   6.709 ms/op
                 existUser·p0.99:   8.932 ms/op
                 existUser·p0.999:  14.874 ms/op
                 existUser·p0.9999: 25.893 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   3: 4.581 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.970 ms/op
                 existUser·p0.50:   4.399 ms/op
                 existUser·p0.90:   5.538 ms/op
                 existUser·p0.95:   6.119 ms/op
                 existUser·p0.99:   7.825 ms/op
                 existUser·p0.999:  12.552 ms/op
                 existUser·p0.9999: 29.394 ms/op
                 existUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 201420
  mean =      4.766 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 121 
    [ 2.500,  5.000) = 142887 
    [ 5.000,  7.500) = 53909 
    [ 7.500, 10.000) = 3507 
    [10.000, 12.500) = 659 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.970 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.865 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     13.739 ms/op
     p(99.9900) =     28.204 ms/op
     p(99.9990) =     29.753 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.251 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 6.132 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.486 ±(99.9%) 0.018 ms/op
Iteration   1: 5.295 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.855 ms/op
                 getUser·p0.50:   4.989 ms/op
                 getUser·p0.90:   6.218 ms/op
                 getUser·p0.95:   7.717 ms/op
                 getUser·p0.99:   12.206 ms/op
                 getUser·p0.999:  26.524 ms/op
                 getUser·p0.9999: 33.620 ms/op
                 getUser·p1.00:   34.996 ms/op

Iteration   2: 4.953 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.646 ms/op
                 getUser·p0.50:   4.719 ms/op
                 getUser·p0.90:   5.849 ms/op
                 getUser·p0.95:   6.627 ms/op
                 getUser·p0.99:   9.825 ms/op
                 getUser·p0.999:  19.540 ms/op
                 getUser·p0.9999: 26.906 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   3: 4.614 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.441 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   6.287 ms/op
                 getUser·p0.99:   9.077 ms/op
                 getUser·p0.999:  20.087 ms/op
                 getUser·p0.9999: 26.378 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 194077
  mean =      4.938 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 130382 
    [ 5.000,  7.500) = 56547 
    [ 7.500, 10.000) = 5052 
    [10.000, 12.500) = 1309 
    [12.500, 15.000) = 400 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.855 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      5.890 ms/op
     p(95.0000) =      6.824 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     24.412 ms/op
     p(99.9900) =     30.166 ms/op
     p(99.9990) =     34.626 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.599 ±(99.9%) 0.246 ms/op
# Warmup Iteration   2: 7.064 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.310 ±(99.9%) 0.024 ms/op
Iteration   1: 6.006 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.773 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   7.274 ms/op
                 listUser·p0.95:   8.356 ms/op
                 listUser·p0.99:   11.757 ms/op
                 listUser·p0.999:  27.648 ms/op
                 listUser·p0.9999: 34.079 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   2: 5.635 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.060 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   6.674 ms/op
                 listUser·p0.95:   7.799 ms/op
                 listUser·p0.99:   10.519 ms/op
                 listUser·p0.999:  25.404 ms/op
                 listUser·p0.9999: 36.984 ms/op
                 listUser·p1.00:   37.618 ms/op

Iteration   3: 5.922 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   5.644 ms/op
                 listUser·p0.90:   7.102 ms/op
                 listUser·p0.95:   7.905 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  19.135 ms/op
                 listUser·p0.9999: 25.041 ms/op
                 listUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 163978
  mean =      5.850 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 26401 
    [ 5.000,  7.500) = 125969 
    [ 7.500, 10.000) = 8684 
    [10.000, 12.500) = 2015 
    [12.500, 15.000) = 416 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      5.505 ms/op
     p(90.0000) =      7.053 ms/op
     p(95.0000) =      8.045 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     25.100 ms/op
     p(99.9900) =     34.249 ms/op
     p(99.9990) =     37.534 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.712 ± 3.663  ops/ms
ClientPb.existUser                       thrpt       3   7.000 ± 5.097  ops/ms
ClientPb.getUser                         thrpt       3   7.493 ± 4.234  ops/ms
ClientPb.listUser                        thrpt       3   6.282 ± 6.002  ops/ms
ClientPb.createUser                       avgt       3   4.263 ± 1.868   ms/op
ClientPb.existUser                        avgt       3   4.175 ± 1.407   ms/op
ClientPb.getUser                          avgt       3   4.512 ± 1.831   ms/op
ClientPb.listUser                         avgt       3   5.369 ± 3.289   ms/op
ClientPb.createUser                     sample  177855   5.393 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.749           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.202           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.398           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.430           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.617           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.512           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.877           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.370           ms/op
ClientPb.existUser                      sample  201420   4.766 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.970           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.563           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.865           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.537           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.749           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.739           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.204           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.950           ms/op
ClientPb.getUser                        sample  194077   4.938 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.855           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.686           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.890           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.824           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.174           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.412           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.166           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.996           ms/op
ClientPb.listUser                       sample  163978   5.850 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.464           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.045           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.059           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.100           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.249           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.618           ms/op
