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
# Warmup Iteration   1: 2.098 ops/ms
# Warmup Iteration   2: 5.796 ops/ms
# Warmup Iteration   3: 8.702 ops/ms
Iteration   1: 9.134 ops/ms
Iteration   2: 9.276 ops/ms
Iteration   3: 9.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.248 ±(99.9%) 1.884 ops/ms [Average]
  (min, avg, max) = (9.134, 9.248, 9.335), stdev = 0.103
  CI (99.9%): [7.364, 11.133] (assumes normal distribution)


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
# Warmup Iteration   1: 2.888 ops/ms
# Warmup Iteration   2: 8.485 ops/ms
# Warmup Iteration   3: 9.291 ops/ms
Iteration   1: 9.640 ops/ms
Iteration   2: 9.441 ops/ms
Iteration   3: 9.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.590 ±(99.9%) 2.391 ops/ms [Average]
  (min, avg, max) = (9.441, 9.590, 9.689), stdev = 0.131
  CI (99.9%): [7.199, 11.981] (assumes normal distribution)


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
# Warmup Iteration   1: 2.633 ops/ms
# Warmup Iteration   2: 8.369 ops/ms
# Warmup Iteration   3: 9.302 ops/ms
Iteration   1: 9.198 ops/ms
Iteration   2: 9.185 ops/ms
Iteration   3: 9.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.268 ±(99.9%) 2.421 ops/ms [Average]
  (min, avg, max) = (9.185, 9.268, 9.421), stdev = 0.133
  CI (99.9%): [6.847, 11.689] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.650 ops/ms
# Warmup Iteration   2: 7.131 ops/ms
# Warmup Iteration   3: 7.584 ops/ms
Iteration   1: 7.759 ops/ms
Iteration   2: 7.972 ops/ms
Iteration   3: 8.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.920 ±(99.9%) 2.587 ops/ms [Average]
  (min, avg, max) = (7.759, 7.920, 8.028), stdev = 0.142
  CI (99.9%): [5.333, 10.506] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.251 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.008 ms/op
Iteration   1: 3.525 ±(99.9%) 0.005 ms/op
Iteration   2: 3.426 ±(99.9%) 0.008 ms/op
Iteration   3: 3.455 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.468 ±(99.9%) 0.924 ms/op [Average]
  (min, avg, max) = (3.426, 3.468, 3.525), stdev = 0.051
  CI (99.9%): [2.544, 4.393] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.536 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.005 ms/op
Iteration   1: 3.209 ±(99.9%) 0.006 ms/op
Iteration   2: 3.289 ±(99.9%) 0.002 ms/op
Iteration   3: 3.304 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.267 ±(99.9%) 0.934 ms/op [Average]
  (min, avg, max) = (3.209, 3.267, 3.304), stdev = 0.051
  CI (99.9%): [2.333, 4.201] (assumes normal distribution)


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
# Warmup Iteration   1: 9.708 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.833 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.006 ms/op
Iteration   1: 3.543 ±(99.9%) 0.007 ms/op
Iteration   2: 3.584 ±(99.9%) 0.009 ms/op
Iteration   3: 3.368 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.498 ±(99.9%) 2.092 ms/op [Average]
  (min, avg, max) = (3.368, 3.498, 3.584), stdev = 0.115
  CI (99.9%): [1.406, 5.590] (assumes normal distribution)


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
# Warmup Iteration   1: 10.050 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.224 ±(99.9%) 0.005 ms/op
Iteration   1: 3.998 ±(99.9%) 0.012 ms/op
Iteration   2: 4.019 ±(99.9%) 0.011 ms/op
Iteration   3: 3.946 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.988 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (3.946, 3.988, 4.019), stdev = 0.038
  CI (99.9%): [3.302, 4.674] (assumes normal distribution)


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
# Warmup Iteration   1: 10.370 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.013 ms/op
Iteration   1: 3.525 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.971 ms/op
                 createUser·p0.999:  21.705 ms/op
                 createUser·p0.9999: 24.667 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   2: 3.477 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.767 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  24.773 ms/op
                 createUser·p0.9999: 31.936 ms/op
                 createUser·p1.00:   32.965 ms/op

Iteration   3: 3.549 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.432 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  19.458 ms/op
                 createUser·p0.9999: 28.279 ms/op
                 createUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272793
  mean =      3.517 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7989 
    [ 2.500,  5.000) = 256120 
    [ 5.000,  7.500) = 7481 
    [ 7.500, 10.000) = 637 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     20.593 ms/op
     p(99.9900) =     30.317 ms/op
     p(99.9990) =     32.804 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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
# Warmup Iteration   1: 9.236 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.008 ms/op
Iteration   1: 3.254 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.192 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  16.831 ms/op
                 existUser·p0.9999: 24.292 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   2: 3.493 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.546 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   6.652 ms/op
                 existUser·p0.999:  21.935 ms/op
                 existUser·p0.9999: 27.121 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   3: 3.363 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.333 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  22.600 ms/op
                 existUser·p0.9999: 27.214 ms/op
                 existUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285011
  mean =      3.367 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9072 
    [ 2.500,  5.000) = 268414 
    [ 5.000,  7.500) = 6447 
    [ 7.500, 10.000) = 609 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 175 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.037 ms/op
     p(99.9000) =     21.233 ms/op
     p(99.9900) =     26.886 ms/op
     p(99.9990) =     28.251 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 8.685 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.786 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.011 ms/op
Iteration   1: 3.568 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   7.266 ms/op
                 getUser·p0.999:  22.151 ms/op
                 getUser·p0.9999: 24.315 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   2: 3.399 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   6.277 ms/op
                 getUser·p0.999:  22.406 ms/op
                 getUser·p0.9999: 25.494 ms/op
                 getUser·p1.00:   26.411 ms/op

Iteration   3: 3.397 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   6.296 ms/op
                 getUser·p0.999:  12.501 ms/op
                 getUser·p0.9999: 32.745 ms/op
                 getUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277959
  mean =      3.453 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2005 
    [ 2.500,  5.000) = 266170 
    [ 5.000,  7.500) = 8188 
    [ 7.500, 10.000) = 972 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 139 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     30.999 ms/op
     p(99.9990) =     33.201 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 10.764 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.556 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.102 ±(99.9%) 0.013 ms/op
Iteration   1: 4.083 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  22.861 ms/op
                 listUser·p0.9999: 25.674 ms/op
                 listUser·p1.00:   26.739 ms/op

Iteration   2: 3.941 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.327 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 16.941 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   3: 3.853 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  15.335 ms/op
                 listUser·p0.9999: 16.346 ms/op
                 listUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242453
  mean =      3.957 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 235184 
    [ 5.000,  7.500) = 5561 
    [ 7.500, 10.000) = 1000 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 242 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.860 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     26.463 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.248 ± 1.884  ops/ms
ClientPb.existUser                       thrpt       3   9.590 ± 2.391  ops/ms
ClientPb.getUser                         thrpt       3   9.268 ± 2.421  ops/ms
ClientPb.listUser                        thrpt       3   7.920 ± 2.587  ops/ms
ClientPb.createUser                       avgt       3   3.468 ± 0.924   ms/op
ClientPb.existUser                        avgt       3   3.267 ± 0.934   ms/op
ClientPb.getUser                          avgt       3   3.498 ± 2.092   ms/op
ClientPb.listUser                         avgt       3   3.988 ± 0.686   ms/op
ClientPb.createUser                     sample  272793   3.517 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.329           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.506           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.087           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.593           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.317           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.965           ms/op
ClientPb.existUser                      sample  285011   3.367 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.192           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.037           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.233           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.886           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.443           ms/op
ClientPb.getUser                        sample  277959   3.453 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.120           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.955           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.840           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.999           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.554           ms/op
ClientPb.listUser                       sample  242453   3.957 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.614           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.860           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.761           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.068           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.739           ms/op
