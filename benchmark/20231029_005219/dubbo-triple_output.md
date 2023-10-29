# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.372 ops/ms
# Warmup Iteration   2: 5.466 ops/ms
# Warmup Iteration   3: 8.732 ops/ms
Iteration   1: 9.774 ops/ms
Iteration   2: 9.794 ops/ms
Iteration   3: 9.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.790 ±(99.9%) 0.265 ops/ms [Average]
  (min, avg, max) = (9.774, 9.790, 9.803), stdev = 0.015
  CI (99.9%): [9.525, 10.055] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.569 ops/ms
# Warmup Iteration   2: 9.331 ops/ms
# Warmup Iteration   3: 10.009 ops/ms
Iteration   1: 10.352 ops/ms
Iteration   2: 10.356 ops/ms
Iteration   3: 10.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.310 ±(99.9%) 1.385 ops/ms [Average]
  (min, avg, max) = (10.222, 10.310, 10.356), stdev = 0.076
  CI (99.9%): [8.925, 11.695] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.270 ops/ms
# Warmup Iteration   2: 9.184 ops/ms
# Warmup Iteration   3: 9.468 ops/ms
Iteration   1: 10.058 ops/ms
Iteration   2: 9.971 ops/ms
Iteration   3: 9.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.983 ±(99.9%) 1.271 ops/ms [Average]
  (min, avg, max) = (9.920, 9.983, 10.058), stdev = 0.070
  CI (99.9%): [8.712, 11.254] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.139 ops/ms
# Warmup Iteration   2: 7.657 ops/ms
# Warmup Iteration   3: 8.322 ops/ms
Iteration   1: 8.475 ops/ms
Iteration   2: 8.550 ops/ms
Iteration   3: 8.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.377 ±(99.9%) 4.341 ops/ms [Average]
  (min, avg, max) = (8.105, 8.377, 8.550), stdev = 0.238
  CI (99.9%): [4.035, 12.718] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.433 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.004 ms/op
Iteration   1: 3.329 ±(99.9%) 0.002 ms/op
Iteration   2: 3.273 ±(99.9%) 0.003 ms/op
Iteration   3: 3.272 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.291 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (3.272, 3.291, 3.329), stdev = 0.032
  CI (99.9%): [2.700, 3.882] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.207 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.414 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.003 ms/op
Iteration   1: 3.097 ±(99.9%) 0.004 ms/op
Iteration   2: 3.128 ±(99.9%) 0.002 ms/op
Iteration   3: 3.218 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.148 ±(99.9%) 1.149 ms/op [Average]
  (min, avg, max) = (3.097, 3.148, 3.218), stdev = 0.063
  CI (99.9%): [1.998, 4.297] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.248 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.437 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.333 ±(99.9%) 0.003 ms/op
Iteration   1: 3.321 ±(99.9%) 0.004 ms/op
Iteration   2: 3.250 ±(99.9%) 0.006 ms/op
Iteration   3: 3.269 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.280 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (3.250, 3.280, 3.321), stdev = 0.037
  CI (99.9%): [2.613, 3.947] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.714 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.004 ms/op
Iteration   1: 3.873 ±(99.9%) 0.005 ms/op
Iteration   2: 3.807 ±(99.9%) 0.006 ms/op
Iteration   3: 3.903 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.861 ±(99.9%) 0.892 ms/op [Average]
  (min, avg, max) = (3.807, 3.861, 3.903), stdev = 0.049
  CI (99.9%): [2.969, 4.753] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.523 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.010 ms/op
Iteration   1: 3.287 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.358 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  10.252 ms/op
                 createUser·p0.9999: 20.906 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 3.264 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.604 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  16.288 ms/op
                 createUser·p0.9999: 23.953 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   3: 3.217 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.489 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.536 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  16.253 ms/op
                 createUser·p0.9999: 35.717 ms/op
                 createUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294829
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18495 
    [ 2.500,  5.000) = 271504 
    [ 5.000,  7.500) = 3876 
    [ 7.500, 10.000) = 396 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.358 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     16.239 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     36.248 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.924 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.008 ms/op
Iteration   1: 3.194 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  11.911 ms/op
                 existUser·p0.9999: 19.759 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   2: 3.228 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  12.788 ms/op
                 existUser·p0.9999: 22.708 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   3: 3.218 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  15.784 ms/op
                 existUser·p0.9999: 21.939 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298875
  mean =      3.213 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14227 
    [ 2.500,  5.000) = 279201 
    [ 5.000,  7.500) = 4589 
    [ 7.500, 10.000) = 327 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.095 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.010 ms/op
Iteration   1: 3.310 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  18.229 ms/op
                 getUser·p0.9999: 21.245 ms/op
                 getUser·p1.00:   21.889 ms/op

Iteration   2: 3.189 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   5.046 ms/op
                 getUser·p0.999:  20.964 ms/op
                 getUser·p0.9999: 23.658 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   3: 3.242 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  10.765 ms/op
                 getUser·p0.9999: 21.168 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295469
  mean =      3.247 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10599 
    [ 2.500,  5.000) = 279382 
    [ 5.000,  7.500) = 4678 
    [ 7.500, 10.000) = 379 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     15.460 ms/op
     p(99.9900) =     22.789 ms/op
     p(99.9990) =     24.521 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.627 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.012 ms/op
Iteration   1: 3.841 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 23.147 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   2: 3.807 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  14.288 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   3: 3.795 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.267 ms/op
                 listUser·p0.999:  13.255 ms/op
                 listUser·p0.9999: 15.385 ms/op
                 listUser·p1.00:   15.450 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251453
  mean =      3.814 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 245305 
    [ 5.000,  7.500) = 4726 
    [ 7.500, 10.000) = 720 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 313 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     14.230 ms/op
     p(99.9900) =     21.131 ms/op
     p(99.9990) =     23.657 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.790 ± 0.265  ops/ms
ClientPb.existUser                       thrpt       3  10.310 ± 1.385  ops/ms
ClientPb.getUser                         thrpt       3   9.983 ± 1.271  ops/ms
ClientPb.listUser                        thrpt       3   8.377 ± 4.341  ops/ms
ClientPb.createUser                       avgt       3   3.291 ± 0.591   ms/op
ClientPb.existUser                        avgt       3   3.148 ± 1.149   ms/op
ClientPb.getUser                          avgt       3   3.280 ± 0.667   ms/op
ClientPb.listUser                         avgt       3   3.861 ± 0.892   ms/op
ClientPb.createUser                     sample  294829   3.256 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.358           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.239           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.406           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.159           ms/op
ClientPb.existUser                      sample  298875   3.213 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.886           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.234           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.533           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.413           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.233           ms/op
ClientPb.getUser                        sample  295469   3.247 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.893           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.600           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.460           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.789           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.838           ms/op
ClientPb.listUser                       sample  251453   3.814 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.284           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.619           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.230           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.131           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.707           ms/op
