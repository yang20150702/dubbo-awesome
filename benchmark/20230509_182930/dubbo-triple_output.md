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
# Warmup Iteration   1: 2.139 ops/ms
# Warmup Iteration   2: 5.962 ops/ms
# Warmup Iteration   3: 8.610 ops/ms
Iteration   1: 9.274 ops/ms
Iteration   2: 9.077 ops/ms
Iteration   3: 9.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.262 ±(99.9%) 3.263 ops/ms [Average]
  (min, avg, max) = (9.077, 9.262, 9.434), stdev = 0.179
  CI (99.9%): [5.999, 12.524] (assumes normal distribution)


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
# Warmup Iteration   1: 3.201 ops/ms
# Warmup Iteration   2: 8.886 ops/ms
# Warmup Iteration   3: 9.651 ops/ms
Iteration   1: 9.373 ops/ms
Iteration   2: 9.682 ops/ms
Iteration   3: 9.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.578 ±(99.9%) 3.237 ops/ms [Average]
  (min, avg, max) = (9.373, 9.578, 9.682), stdev = 0.177
  CI (99.9%): [6.341, 12.815] (assumes normal distribution)


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
# Warmup Iteration   1: 2.939 ops/ms
# Warmup Iteration   2: 8.833 ops/ms
# Warmup Iteration   3: 9.232 ops/ms
Iteration   1: 9.264 ops/ms
Iteration   2: 9.274 ops/ms
Iteration   3: 9.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.229 ±(99.9%) 1.287 ops/ms [Average]
  (min, avg, max) = (9.147, 9.229, 9.274), stdev = 0.071
  CI (99.9%): [7.942, 10.515] (assumes normal distribution)


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
# Warmup Iteration   1: 2.747 ops/ms
# Warmup Iteration   2: 7.232 ops/ms
# Warmup Iteration   3: 7.979 ops/ms
Iteration   1: 7.941 ops/ms
Iteration   2: 8.203 ops/ms
Iteration   3: 8.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.126 ±(99.9%) 2.935 ops/ms [Average]
  (min, avg, max) = (7.941, 8.126, 8.234), stdev = 0.161
  CI (99.9%): [5.191, 11.061] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.926 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.748 ±(99.9%) 0.006 ms/op
Iteration   1: 3.470 ±(99.9%) 0.006 ms/op
Iteration   2: 3.353 ±(99.9%) 0.012 ms/op
Iteration   3: 3.440 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.421 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (3.353, 3.421, 3.470), stdev = 0.061
  CI (99.9%): [2.309, 4.534] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.559 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.610 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.010 ms/op
Iteration   1: 3.202 ±(99.9%) 0.008 ms/op
Iteration   2: 3.107 ±(99.9%) 0.008 ms/op
Iteration   3: 3.312 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.207 ±(99.9%) 1.865 ms/op [Average]
  (min, avg, max) = (3.107, 3.207, 3.312), stdev = 0.102
  CI (99.9%): [1.342, 5.072] (assumes normal distribution)


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
# Warmup Iteration   1: 8.792 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.004 ms/op
Iteration   1: 3.285 ±(99.9%) 0.008 ms/op
Iteration   2: 3.282 ±(99.9%) 0.008 ms/op
Iteration   3: 3.413 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.327 ±(99.9%) 1.358 ms/op [Average]
  (min, avg, max) = (3.282, 3.327, 3.413), stdev = 0.074
  CI (99.9%): [1.969, 4.685] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.773 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.224 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.010 ms/op
Iteration   1: 4.039 ±(99.9%) 0.010 ms/op
Iteration   2: 3.873 ±(99.9%) 0.013 ms/op
Iteration   3: 3.898 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.937 ±(99.9%) 1.634 ms/op [Average]
  (min, avg, max) = (3.873, 3.937, 4.039), stdev = 0.090
  CI (99.9%): [2.303, 5.571] (assumes normal distribution)


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
# Warmup Iteration   1: 10.113 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.010 ms/op
Iteration   1: 3.525 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   5.628 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  23.681 ms/op
                 createUser·p0.9999: 32.768 ms/op
                 createUser·p1.00:   33.554 ms/op

Iteration   2: 3.456 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  20.710 ms/op
                 createUser·p0.9999: 24.207 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   3: 3.337 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  18.574 ms/op
                 createUser·p0.9999: 26.466 ms/op
                 createUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278926
  mean =      3.438 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16696 
    [ 2.500,  5.000) = 251347 
    [ 5.000,  7.500) = 9655 
    [ 7.500, 10.000) = 703 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     20.286 ms/op
     p(99.9900) =     30.735 ms/op
     p(99.9990) =     33.341 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 9.404 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.009 ms/op
Iteration   1: 3.284 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  9.168 ms/op
                 existUser·p0.9999: 22.184 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   2: 3.216 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  12.478 ms/op
                 existUser·p0.9999: 25.004 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   3: 3.223 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.393 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  12.482 ms/op
                 existUser·p0.9999: 29.270 ms/op
                 existUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296031
  mean =      3.241 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10023 
    [ 2.500,  5.000) = 281636 
    [ 5.000,  7.500) = 3810 
    [ 7.500, 10.000) = 235 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     12.460 ms/op
     p(99.9900) =     27.866 ms/op
     p(99.9990) =     29.798 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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
# Warmup Iteration   1: 9.248 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.009 ms/op
Iteration   1: 3.487 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.704 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.582 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  19.333 ms/op
                 getUser·p0.9999: 21.982 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   2: 3.406 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  9.437 ms/op
                 getUser·p0.9999: 23.790 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   3: 3.323 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  16.502 ms/op
                 getUser·p0.9999: 25.965 ms/op
                 getUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281910
  mean =      3.404 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16050 
    [ 2.500,  5.000) = 257675 
    [ 5.000,  7.500) = 7059 
    [ 7.500, 10.000) = 782 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     12.176 ms/op
     p(99.9900) =     24.760 ms/op
     p(99.9990) =     26.926 ms/op
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
# Warmup Iteration   1: 9.861 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.409 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.012 ms/op
Iteration   1: 3.934 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  21.842 ms/op
                 listUser·p0.9999: 24.407 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   2: 3.795 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.332 ms/op
                 listUser·p0.999:  13.776 ms/op
                 listUser·p0.9999: 16.253 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   3: 3.843 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  15.115 ms/op
                 listUser·p0.9999: 19.912 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248870
  mean =      3.857 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 242656 
    [ 5.000,  7.500) = 4483 
    [ 7.500, 10.000) = 962 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 211 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     15.794 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     25.200 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.262 ± 3.263  ops/ms
ClientPb.existUser                       thrpt       3   9.578 ± 3.237  ops/ms
ClientPb.getUser                         thrpt       3   9.229 ± 1.287  ops/ms
ClientPb.listUser                        thrpt       3   8.126 ± 2.935  ops/ms
ClientPb.createUser                       avgt       3   3.421 ± 1.112   ms/op
ClientPb.existUser                        avgt       3   3.207 ± 1.865   ms/op
ClientPb.getUser                          avgt       3   3.327 ± 1.358   ms/op
ClientPb.listUser                         avgt       3   3.937 ± 1.634   ms/op
ClientPb.createUser                     sample  278926   3.438 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.724           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.775           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.286           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.735           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.554           ms/op
ClientPb.existUser                      sample  296031   3.241 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.141           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.460           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.866           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.245           ms/op
ClientPb.getUser                        sample  281910   3.404 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.110           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.341           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.176           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.760           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.165           ms/op
ClientPb.listUser                       sample  248870   3.857 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.212           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.772           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.153           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.816           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.794           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.757           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.082           ms/op
