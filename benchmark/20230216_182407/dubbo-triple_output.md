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
# Warmup Iteration   1: 2.382 ops/ms
# Warmup Iteration   2: 5.953 ops/ms
# Warmup Iteration   3: 9.554 ops/ms
Iteration   1: 9.572 ops/ms
Iteration   2: 10.177 ops/ms
Iteration   3: 10.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.949 ±(99.9%) 6.006 ops/ms [Average]
  (min, avg, max) = (9.572, 9.949, 10.177), stdev = 0.329
  CI (99.9%): [3.943, 15.955] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.643 ops/ms
# Warmup Iteration   2: 9.604 ops/ms
# Warmup Iteration   3: 9.771 ops/ms
Iteration   1: 10.637 ops/ms
Iteration   2: 10.337 ops/ms
Iteration   3: 10.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.381 ±(99.9%) 4.329 ops/ms [Average]
  (min, avg, max) = (10.168, 10.381, 10.637), stdev = 0.237
  CI (99.9%): [6.052, 14.709] (assumes normal distribution)


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
# Warmup Iteration   1: 3.604 ops/ms
# Warmup Iteration   2: 8.741 ops/ms
# Warmup Iteration   3: 9.562 ops/ms
Iteration   1: 10.093 ops/ms
Iteration   2: 9.388 ops/ms
Iteration   3: 10.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.893 ±(99.9%) 8.039 ops/ms [Average]
  (min, avg, max) = (9.388, 9.893, 10.199), stdev = 0.441
  CI (99.9%): [1.855, 17.932] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.452 ops/ms
# Warmup Iteration   2: 7.736 ops/ms
# Warmup Iteration   3: 8.392 ops/ms
Iteration   1: 8.534 ops/ms
Iteration   2: 8.496 ops/ms
Iteration   3: 8.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.605 ±(99.9%) 2.860 ops/ms [Average]
  (min, avg, max) = (8.496, 8.605, 8.784), stdev = 0.157
  CI (99.9%): [5.745, 11.465] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.507 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.432 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
Iteration   1: 3.196 ±(99.9%) 0.004 ms/op
Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
Iteration   3: 3.153 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.181 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (3.153, 3.181, 3.196), stdev = 0.024
  CI (99.9%): [2.748, 3.614] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.812 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.003 ms/op
Iteration   1: 3.088 ±(99.9%) 0.004 ms/op
Iteration   2: 3.019 ±(99.9%) 0.007 ms/op
Iteration   3: 3.031 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.046 ±(99.9%) 0.669 ms/op [Average]
  (min, avg, max) = (3.019, 3.046, 3.088), stdev = 0.037
  CI (99.9%): [2.376, 3.715] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.751 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.002 ms/op
Iteration   1: 3.335 ±(99.9%) 0.003 ms/op
Iteration   2: 3.195 ±(99.9%) 0.004 ms/op
Iteration   3: 3.196 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.242 ±(99.9%) 1.469 ms/op [Average]
  (min, avg, max) = (3.195, 3.242, 3.335), stdev = 0.081
  CI (99.9%): [1.773, 4.712] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.864 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.004 ms/op
Iteration   1: 3.645 ±(99.9%) 0.012 ms/op
Iteration   2: 3.696 ±(99.9%) 0.005 ms/op
Iteration   3: 3.730 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.690 ±(99.9%) 0.780 ms/op [Average]
  (min, avg, max) = (3.645, 3.690, 3.730), stdev = 0.043
  CI (99.9%): [2.911, 4.470] (assumes normal distribution)


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
# Warmup Iteration   1: 8.157 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
Iteration   1: 3.245 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.354 ms/op
                 createUser·p0.999:  19.137 ms/op
                 createUser·p0.9999: 21.299 ms/op
                 createUser·p1.00:   21.823 ms/op

Iteration   2: 3.306 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.298 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  16.725 ms/op
                 createUser·p0.9999: 24.290 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   3: 3.153 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  14.837 ms/op
                 createUser·p0.9999: 19.492 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296785
  mean =      3.233 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23332 
    [ 2.500,  5.000) = 267279 
    [ 5.000,  7.500) = 5200 
    [ 7.500, 10.000) = 396 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.298 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     16.850 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     24.612 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 6.901 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
Iteration   1: 3.047 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.367 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  9.814 ms/op
                 existUser·p0.9999: 20.071 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   2: 3.069 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  10.125 ms/op
                 existUser·p0.9999: 22.262 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.718 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.326 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  8.307 ms/op
                 existUser·p0.9999: 26.469 ms/op
                 existUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311440
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26556 
    [ 2.500,  5.000) = 279483 
    [ 5.000,  7.500) = 4793 
    [ 7.500, 10.000) = 308 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.219 ms/op
     p(95.0000) =      3.404 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     25.812 ms/op
     p(99.9990) =     27.030 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 7.214 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.010 ms/op
Iteration   1: 3.314 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  18.317 ms/op
                 getUser·p0.9999: 24.248 ms/op
                 getUser·p1.00:   25.264 ms/op

Iteration   2: 3.169 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.657 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   5.720 ms/op
                 getUser·p0.999:  10.936 ms/op
                 getUser·p0.9999: 26.045 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   3: 3.162 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.759 ms/op
                 getUser·p0.999:  11.806 ms/op
                 getUser·p0.9999: 24.179 ms/op
                 getUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298497
  mean =      3.213 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13695 
    [ 2.500,  5.000) = 278484 
    [ 5.000,  7.500) = 5110 
    [ 7.500, 10.000) = 734 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     25.072 ms/op
     p(99.9990) =     26.676 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 9.757 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.012 ms/op
Iteration   1: 3.698 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.137 ms/op
                 listUser·p0.99:   5.915 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 23.759 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   2: 3.795 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.042 ms/op
                 listUser·p0.999:  13.559 ms/op
                 listUser·p0.9999: 18.302 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 3.841 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.845 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.255 ms/op
                 listUser·p0.999:  14.889 ms/op
                 listUser·p0.9999: 21.692 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254062
  mean =      3.777 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 247824 
    [ 5.000,  7.500) = 4530 
    [ 7.500, 10.000) = 902 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.949 ± 6.006  ops/ms
ClientPb.existUser                       thrpt       3  10.381 ± 4.329  ops/ms
ClientPb.getUser                         thrpt       3   9.893 ± 8.039  ops/ms
ClientPb.listUser                        thrpt       3   8.605 ± 2.860  ops/ms
ClientPb.createUser                       avgt       3   3.181 ± 0.433   ms/op
ClientPb.existUser                        avgt       3   3.046 ± 0.669   ms/op
ClientPb.getUser                          avgt       3   3.242 ± 1.469   ms/op
ClientPb.listUser                         avgt       3   3.690 ± 0.780   ms/op
ClientPb.createUser                     sample  296785   3.233 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.298           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.850           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.233           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.559           ms/op
ClientPb.existUser                      sample  311440   3.079 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.104           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.404           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.798           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.812           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.410           ms/op
ClientPb.getUser                        sample  298497   3.213 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.037           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.539           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.186           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.072           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.935           ms/op
ClientPb.listUser                       sample  254062   3.777 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.055           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.849           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.762           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.675           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.347           ms/op
