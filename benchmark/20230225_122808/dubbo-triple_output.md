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
# Warmup Iteration   1: 2.214 ops/ms
# Warmup Iteration   2: 6.025 ops/ms
# Warmup Iteration   3: 8.664 ops/ms
Iteration   1: 9.227 ops/ms
Iteration   2: 9.431 ops/ms
Iteration   3: 9.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.400 ±(99.9%) 2.917 ops/ms [Average]
  (min, avg, max) = (9.227, 9.400, 9.543), stdev = 0.160
  CI (99.9%): [6.483, 12.317] (assumes normal distribution)


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
# Warmup Iteration   1: 3.003 ops/ms
# Warmup Iteration   2: 8.525 ops/ms
# Warmup Iteration   3: 9.364 ops/ms
Iteration   1: 9.862 ops/ms
Iteration   2: 9.918 ops/ms
Iteration   3: 9.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.846 ±(99.9%) 1.469 ops/ms [Average]
  (min, avg, max) = (9.759, 9.846, 9.918), stdev = 0.080
  CI (99.9%): [8.378, 11.315] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.821 ops/ms
# Warmup Iteration   2: 8.141 ops/ms
# Warmup Iteration   3: 8.734 ops/ms
Iteration   1: 9.435 ops/ms
Iteration   2: 9.155 ops/ms
Iteration   3: 9.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.265 ±(99.9%) 2.722 ops/ms [Average]
  (min, avg, max) = (9.155, 9.265, 9.435), stdev = 0.149
  CI (99.9%): [6.544, 11.987] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.716 ops/ms
# Warmup Iteration   2: 7.226 ops/ms
# Warmup Iteration   3: 8.061 ops/ms
Iteration   1: 7.920 ops/ms
Iteration   2: 8.024 ops/ms
Iteration   3: 8.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.005 ±(99.9%) 1.413 ops/ms [Average]
  (min, avg, max) = (7.920, 8.005, 8.071), stdev = 0.077
  CI (99.9%): [6.593, 9.418] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.623 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.009 ms/op
Iteration   1: 3.424 ±(99.9%) 0.010 ms/op
Iteration   2: 3.405 ±(99.9%) 0.008 ms/op
Iteration   3: 3.327 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.386 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.327, 3.386, 3.424), stdev = 0.051
  CI (99.9%): [2.447, 4.324] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.791 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.006 ms/op
Iteration   1: 3.256 ±(99.9%) 0.009 ms/op
Iteration   2: 3.259 ±(99.9%) 0.006 ms/op
Iteration   3: 3.347 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.288 ±(99.9%) 0.940 ms/op [Average]
  (min, avg, max) = (3.256, 3.288, 3.347), stdev = 0.052
  CI (99.9%): [2.348, 4.228] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.755 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.003 ms/op
Iteration   1: 3.461 ±(99.9%) 0.005 ms/op
Iteration   2: 3.420 ±(99.9%) 0.008 ms/op
Iteration   3: 3.399 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.427 ±(99.9%) 0.583 ms/op [Average]
  (min, avg, max) = (3.399, 3.427, 3.461), stdev = 0.032
  CI (99.9%): [2.844, 4.009] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.710 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.301 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.012 ms/op
Iteration   1: 3.988 ±(99.9%) 0.006 ms/op
Iteration   2: 3.879 ±(99.9%) 0.011 ms/op
Iteration   3: 3.986 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.951 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.879, 3.951, 3.988), stdev = 0.062
  CI (99.9%): [2.816, 5.087] (assumes normal distribution)


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
# Warmup Iteration   1: 9.461 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.009 ms/op
Iteration   1: 3.498 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.561 ms/op
                 createUser·p0.999:  21.004 ms/op
                 createUser·p0.9999: 23.032 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   2: 3.255 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.452 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  13.156 ms/op
                 createUser·p0.9999: 24.615 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   3: 3.399 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.675 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.135 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  17.155 ms/op
                 createUser·p0.9999: 24.923 ms/op
                 createUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283617
  mean =      3.381 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12405 
    [ 2.500,  5.000) = 265311 
    [ 5.000,  7.500) = 4779 
    [ 7.500, 10.000) = 571 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     18.002 ms/op
     p(99.9900) =     24.597 ms/op
     p(99.9990) =     26.192 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 8.979 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.008 ms/op
Iteration   1: 3.338 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  16.777 ms/op
                 existUser·p0.9999: 27.361 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   2: 3.322 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  16.972 ms/op
                 existUser·p0.9999: 21.443 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   3: 3.337 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  20.912 ms/op
                 existUser·p0.9999: 28.882 ms/op
                 existUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287812
  mean =      3.332 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11938 
    [ 2.500,  5.000) = 271201 
    [ 5.000,  7.500) = 3906 
    [ 7.500, 10.000) = 355 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     16.770 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     29.757 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 9.953 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.010 ms/op
Iteration   1: 3.531 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.972 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   5.223 ms/op
                 getUser·p0.99:   7.185 ms/op
                 getUser·p0.999:  21.629 ms/op
                 getUser·p0.9999: 28.211 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   2: 3.386 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  20.773 ms/op
                 getUser·p0.9999: 24.317 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   3: 3.375 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.751 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  18.822 ms/op
                 getUser·p0.9999: 25.543 ms/op
                 getUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279910
  mean =      3.429 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15289 
    [ 2.500,  5.000) = 255195 
    [ 5.000,  7.500) = 8131 
    [ 7.500, 10.000) = 863 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 136 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     19.726 ms/op
     p(99.9900) =     25.396 ms/op
     p(99.9990) =     28.829 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 11.545 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.485 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.016 ms/op
Iteration   1: 4.077 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  20.860 ms/op
                 listUser·p0.9999: 25.531 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   2: 3.849 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  15.498 ms/op
                 listUser·p0.9999: 18.078 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 3.920 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  15.113 ms/op
                 listUser·p0.9999: 19.562 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243031
  mean =      3.946 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 234883 
    [ 5.000,  7.500) = 5802 
    [ 7.500, 10.000) = 1442 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      2.187 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     15.924 ms/op
     p(99.9900) =     24.284 ms/op
     p(99.9990) =     26.107 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.400 ± 2.917  ops/ms
ClientPb.existUser                       thrpt       3   9.846 ± 1.469  ops/ms
ClientPb.getUser                         thrpt       3   9.265 ± 2.722  ops/ms
ClientPb.listUser                        thrpt       3   8.005 ± 1.413  ops/ms
ClientPb.createUser                       avgt       3   3.386 ± 0.939   ms/op
ClientPb.existUser                        avgt       3   3.288 ± 0.940   ms/op
ClientPb.getUser                          avgt       3   3.427 ± 0.583   ms/op
ClientPb.listUser                         avgt       3   3.951 ± 1.135   ms/op
ClientPb.createUser                     sample  283617   3.381 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.352           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.002           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.597           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.132           ms/op
ClientPb.existUser                      sample  287812   3.332 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.867           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.969           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.770           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.394           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.884           ms/op
ClientPb.getUser                        sample  279910   3.429 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.319           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.341           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.726           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.396           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.967           ms/op
ClientPb.listUser                       sample  243031   3.946 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.187           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.924           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.284           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.575           ms/op
