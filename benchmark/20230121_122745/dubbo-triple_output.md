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
# Warmup Iteration   1: 1.071 ops/ms
# Warmup Iteration   2: 2.543 ops/ms
# Warmup Iteration   3: 5.403 ops/ms
Iteration   1: 5.727 ops/ms
Iteration   2: 5.940 ops/ms
Iteration   3: 5.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.826 ±(99.9%) 1.962 ops/ms [Average]
  (min, avg, max) = (5.727, 5.826, 5.940), stdev = 0.108
  CI (99.9%): [3.865, 7.788] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.693 ops/ms
# Warmup Iteration   2: 4.880 ops/ms
# Warmup Iteration   3: 5.837 ops/ms
Iteration   1: 6.244 ops/ms
Iteration   2: 6.227 ops/ms
Iteration   3: 6.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.276 ±(99.9%) 1.295 ops/ms [Average]
  (min, avg, max) = (6.227, 6.276, 6.357), stdev = 0.071
  CI (99.9%): [4.981, 7.571] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.504 ops/ms
# Warmup Iteration   2: 5.261 ops/ms
# Warmup Iteration   3: 5.833 ops/ms
Iteration   1: 5.834 ops/ms
Iteration   2: 5.910 ops/ms
Iteration   3: 5.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.889 ±(99.9%) 0.880 ops/ms [Average]
  (min, avg, max) = (5.834, 5.889, 5.923), stdev = 0.048
  CI (99.9%): [5.008, 6.769] (assumes normal distribution)


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
# Warmup Iteration   1: 1.597 ops/ms
# Warmup Iteration   2: 4.276 ops/ms
# Warmup Iteration   3: 5.069 ops/ms
Iteration   1: 4.916 ops/ms
Iteration   2: 5.128 ops/ms
Iteration   3: 5.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.084 ±(99.9%) 2.752 ops/ms [Average]
  (min, avg, max) = (4.916, 5.084, 5.208), stdev = 0.151
  CI (99.9%): [2.332, 7.836] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 18.344 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.500 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.592 ±(99.9%) 0.014 ms/op
Iteration   1: 5.514 ±(99.9%) 0.018 ms/op
Iteration   2: 5.526 ±(99.9%) 0.010 ms/op
Iteration   3: 5.609 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.550 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (5.514, 5.550, 5.609), stdev = 0.051
  CI (99.9%): [4.610, 6.489] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 17.126 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.237 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.358 ±(99.9%) 0.016 ms/op
Iteration   1: 5.218 ±(99.9%) 0.009 ms/op
Iteration   2: 5.303 ±(99.9%) 0.010 ms/op
Iteration   3: 5.354 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.292 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (5.218, 5.292, 5.354), stdev = 0.069
  CI (99.9%): [4.041, 6.543] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.562 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.938 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.387 ±(99.9%) 0.015 ms/op
Iteration   1: 5.511 ±(99.9%) 0.011 ms/op
Iteration   2: 5.399 ±(99.9%) 0.017 ms/op
Iteration   3: 5.345 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.418 ±(99.9%) 1.547 ms/op [Average]
  (min, avg, max) = (5.345, 5.418, 5.511), stdev = 0.085
  CI (99.9%): [3.871, 6.965] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.935 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 7.170 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.703 ±(99.9%) 0.014 ms/op
Iteration   1: 6.223 ±(99.9%) 0.016 ms/op
Iteration   2: 6.330 ±(99.9%) 0.016 ms/op
Iteration   3: 6.340 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.297 ±(99.9%) 1.183 ms/op [Average]
  (min, avg, max) = (6.223, 6.297, 6.340), stdev = 0.065
  CI (99.9%): [5.114, 7.481] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.628 ±(99.9%) 0.334 ms/op
# Warmup Iteration   2: 7.513 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 5.611 ±(99.9%) 0.023 ms/op
Iteration   1: 5.320 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.769 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.709 ms/op
                 createUser·p0.95:   7.741 ms/op
                 createUser·p0.99:   10.437 ms/op
                 createUser·p0.999:  24.521 ms/op
                 createUser·p0.9999: 28.475 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   2: 5.599 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   7.086 ms/op
                 createUser·p0.95:   8.454 ms/op
                 createUser·p0.99:   10.960 ms/op
                 createUser·p0.999:  25.395 ms/op
                 createUser·p0.9999: 29.651 ms/op
                 createUser·p1.00:   30.114 ms/op

Iteration   3: 5.405 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   4.989 ms/op
                 createUser·p0.90:   6.726 ms/op
                 createUser·p0.95:   7.709 ms/op
                 createUser·p0.99:   10.675 ms/op
                 createUser·p0.999:  26.502 ms/op
                 createUser·p0.9999: 32.902 ms/op
                 createUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176495
  mean =      5.439 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 86202 
    [ 5.000,  7.500) = 78904 
    [ 7.500, 10.000) = 8891 
    [10.000, 12.500) = 1553 
    [12.500, 15.000) = 525 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =      7.922 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     25.330 ms/op
     p(99.9900) =     31.621 ms/op
     p(99.9990) =     33.390 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 19.531 ±(99.9%) 0.382 ms/op
# Warmup Iteration   2: 6.057 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.466 ±(99.9%) 0.021 ms/op
Iteration   1: 5.291 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.421 ms/op
                 existUser·p0.50:   4.915 ms/op
                 existUser·p0.90:   6.636 ms/op
                 existUser·p0.95:   7.774 ms/op
                 existUser·p0.99:   10.617 ms/op
                 existUser·p0.999:  21.479 ms/op
                 existUser·p0.9999: 38.008 ms/op
                 existUser·p1.00:   39.911 ms/op

Iteration   2: 5.345 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.488 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.980 ms/op
                 existUser·p0.95:   7.987 ms/op
                 existUser·p0.99:   10.387 ms/op
                 existUser·p0.999:  23.175 ms/op
                 existUser·p0.9999: 35.394 ms/op
                 existUser·p1.00:   37.487 ms/op

Iteration   3: 5.408 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.257 ms/op
                 existUser·p0.50:   5.038 ms/op
                 existUser·p0.90:   6.939 ms/op
                 existUser·p0.95:   7.946 ms/op
                 existUser·p0.99:   10.355 ms/op
                 existUser·p0.999:  25.330 ms/op
                 existUser·p0.9999: 32.309 ms/op
                 existUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179479
  mean =      5.348 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 93856 
    [ 5.000,  7.500) = 73636 
    [ 7.500, 10.000) = 9701 
    [10.000, 12.500) = 1541 
    [12.500, 15.000) = 351 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      7.905 ms/op
     p(99.0000) =     10.404 ms/op
     p(99.9000) =     21.907 ms/op
     p(99.9900) =     37.487 ms/op
     p(99.9990) =     39.703 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.371 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 6.339 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.542 ±(99.9%) 0.019 ms/op
Iteration   1: 5.583 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.503 ms/op
                 getUser·p0.50:   5.169 ms/op
                 getUser·p0.90:   7.078 ms/op
                 getUser·p0.95:   8.618 ms/op
                 getUser·p0.99:   12.108 ms/op
                 getUser·p0.999:  22.627 ms/op
                 getUser·p0.9999: 25.815 ms/op
                 getUser·p1.00:   26.247 ms/op

Iteration   2: 5.859 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.470 ms/op
                 getUser·p0.50:   5.464 ms/op
                 getUser·p0.90:   7.643 ms/op
                 getUser·p0.95:   8.716 ms/op
                 getUser·p0.99:   11.794 ms/op
                 getUser·p0.999:  25.060 ms/op
                 getUser·p0.9999: 38.848 ms/op
                 getUser·p1.00:   42.992 ms/op

Iteration   3: 5.583 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.318 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   7.315 ms/op
                 getUser·p0.95:   8.331 ms/op
                 getUser·p0.99:   11.285 ms/op
                 getUser·p0.999:  19.595 ms/op
                 getUser·p0.9999: 29.190 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169179
  mean =      5.672 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 59223 
    [ 5.000, 10.000) = 106157 
    [10.000, 15.000) = 3193 
    [15.000, 20.000) = 364 
    [20.000, 25.000) = 141 
    [25.000, 30.000) = 79 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.318 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      7.397 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     11.665 ms/op
     p(99.9000) =     22.807 ms/op
     p(99.9900) =     33.074 ms/op
     p(99.9990) =     42.221 ms/op
     p(99.9999) =     42.992 ms/op
    p(100.0000) =     42.992 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.360 ±(99.9%) 0.387 ms/op
# Warmup Iteration   2: 7.470 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 6.315 ±(99.9%) 0.026 ms/op
Iteration   1: 6.765 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.736 ms/op
                 listUser·p0.50:   6.242 ms/op
                 listUser·p0.90:   9.110 ms/op
                 listUser·p0.95:   10.387 ms/op
                 listUser·p0.99:   13.763 ms/op
                 listUser·p0.999:  25.985 ms/op
                 listUser·p0.9999: 28.731 ms/op
                 listUser·p1.00:   29.426 ms/op

Iteration   2: 6.292 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.666 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   8.004 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   12.190 ms/op
                 listUser·p0.999:  28.053 ms/op
                 listUser·p0.9999: 36.016 ms/op
                 listUser·p1.00:   37.618 ms/op

Iteration   3: 6.282 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.211 ms/op
                 listUser·p0.50:   5.874 ms/op
                 listUser·p0.90:   7.643 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   12.150 ms/op
                 listUser·p0.999:  23.953 ms/op
                 listUser·p0.9999: 27.388 ms/op
                 listUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149118
  mean =      6.438 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 6327 
    [ 5.000,  7.500) = 121895 
    [ 7.500, 10.000) = 14860 
    [10.000, 12.500) = 4402 
    [12.500, 15.000) = 959 
    [15.000, 17.500) = 261 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 128 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      2.666 ms/op
     p(50.0000) =      5.972 ms/op
     p(90.0000) =      8.167 ms/op
     p(95.0000) =      9.568 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     26.116 ms/op
     p(99.9900) =     32.587 ms/op
     p(99.9990) =     36.942 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.826 ± 1.962  ops/ms
ClientPb.existUser                       thrpt       3   6.276 ± 1.295  ops/ms
ClientPb.getUser                         thrpt       3   5.889 ± 0.880  ops/ms
ClientPb.listUser                        thrpt       3   5.084 ± 2.752  ops/ms
ClientPb.createUser                       avgt       3   5.550 ± 0.939   ms/op
ClientPb.existUser                        avgt       3   5.292 ± 1.251   ms/op
ClientPb.getUser                          avgt       3   5.418 ± 1.547   ms/op
ClientPb.listUser                         avgt       3   6.297 ± 1.183   ms/op
ClientPb.createUser                     sample  176495   5.439 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.309           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.022           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.849           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.922           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.715           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.330           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.621           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.669           ms/op
ClientPb.existUser                      sample  179479   5.348 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.488           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.964           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.857           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.905           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.404           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.907           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.487           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.911           ms/op
ClientPb.getUser                        sample  169179   5.672 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.318           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.267           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.397           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.536           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.665           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.807           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.074           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.992           ms/op
ClientPb.listUser                       sample  149118   6.438 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.666           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.972           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.167           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.568           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.730           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.116           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.587           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.618           ms/op
