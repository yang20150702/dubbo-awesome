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
# Warmup Iteration   1: 1.050 ops/ms
# Warmup Iteration   2: 2.337 ops/ms
# Warmup Iteration   3: 4.610 ops/ms
Iteration   1: 5.009 ops/ms
Iteration   2: 5.510 ops/ms
Iteration   3: 5.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.494 ±(99.9%) 8.692 ops/ms [Average]
  (min, avg, max) = (5.009, 5.494, 5.962), stdev = 0.476
  CI (99.9%): [≈ 0, 14.186] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.705 ops/ms
# Warmup Iteration   2: 4.485 ops/ms
# Warmup Iteration   3: 6.051 ops/ms
Iteration   1: 6.003 ops/ms
Iteration   2: 6.067 ops/ms
Iteration   3: 5.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.949 ±(99.9%) 2.790 ops/ms [Average]
  (min, avg, max) = (5.776, 5.949, 6.067), stdev = 0.153
  CI (99.9%): [3.159, 8.739] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.595 ops/ms
# Warmup Iteration   2: 4.154 ops/ms
# Warmup Iteration   3: 5.529 ops/ms
Iteration   1: 5.705 ops/ms
Iteration   2: 5.764 ops/ms
Iteration   3: 5.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.691 ±(99.9%) 1.472 ops/ms [Average]
  (min, avg, max) = (5.605, 5.691, 5.764), stdev = 0.081
  CI (99.9%): [4.219, 7.163] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.538 ops/ms
# Warmup Iteration   2: 3.904 ops/ms
# Warmup Iteration   3: 4.708 ops/ms
Iteration   1: 4.789 ops/ms
Iteration   2: 4.711 ops/ms
Iteration   3: 4.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.763 ±(99.9%) 0.819 ops/ms [Average]
  (min, avg, max) = (4.711, 4.763, 4.789), stdev = 0.045
  CI (99.9%): [3.944, 5.581] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 19.904 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 7.385 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.731 ±(99.9%) 0.016 ms/op
Iteration   1: 5.768 ±(99.9%) 0.010 ms/op
Iteration   2: 5.501 ±(99.9%) 0.010 ms/op
Iteration   3: 5.556 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.608 ±(99.9%) 2.578 ms/op [Average]
  (min, avg, max) = (5.501, 5.608, 5.768), stdev = 0.141
  CI (99.9%): [3.030, 8.186] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.813 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 6.477 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.600 ±(99.9%) 0.010 ms/op
Iteration   1: 5.267 ±(99.9%) 0.012 ms/op
Iteration   2: 5.412 ±(99.9%) 0.008 ms/op
Iteration   3: 5.309 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.329 ±(99.9%) 1.362 ms/op [Average]
  (min, avg, max) = (5.267, 5.329, 5.412), stdev = 0.075
  CI (99.9%): [3.967, 6.691] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.119 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.331 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.410 ±(99.9%) 0.013 ms/op
Iteration   1: 5.684 ±(99.9%) 0.011 ms/op
Iteration   2: 5.872 ±(99.9%) 0.010 ms/op
Iteration   3: 5.451 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.669 ±(99.9%) 3.842 ms/op [Average]
  (min, avg, max) = (5.451, 5.669, 5.872), stdev = 0.211
  CI (99.9%): [1.826, 9.511] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 20.089 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 7.415 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.571 ±(99.9%) 0.013 ms/op
Iteration   1: 6.183 ±(99.9%) 0.018 ms/op
Iteration   2: 6.188 ±(99.9%) 0.015 ms/op
Iteration   3: 6.211 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.194 ±(99.9%) 0.273 ms/op [Average]
  (min, avg, max) = (6.183, 6.194, 6.211), stdev = 0.015
  CI (99.9%): [5.921, 6.468] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 18.025 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 7.157 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.173 ±(99.9%) 0.029 ms/op
Iteration   1: 5.618 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.642 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   7.209 ms/op
                 createUser·p0.95:   8.380 ms/op
                 createUser·p0.99:   11.207 ms/op
                 createUser·p0.999:  22.087 ms/op
                 createUser·p0.9999: 24.019 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 5.644 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   8.159 ms/op
                 createUser·p0.99:   11.092 ms/op
                 createUser·p0.999:  27.765 ms/op
                 createUser·p0.9999: 35.673 ms/op
                 createUser·p1.00:   38.076 ms/op

Iteration   3: 5.497 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.413 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   6.734 ms/op
                 createUser·p0.95:   7.406 ms/op
                 createUser·p0.99:   10.426 ms/op
                 createUser·p0.999:  17.558 ms/op
                 createUser·p0.9999: 25.532 ms/op
                 createUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171778
  mean =      5.586 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 61117 
    [ 5.000,  7.500) = 99149 
    [ 7.500, 10.000) = 8655 
    [10.000, 12.500) = 1934 
    [12.500, 15.000) = 495 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.671 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      6.963 ms/op
     p(95.0000) =      7.963 ms/op
     p(99.0000) =     10.928 ms/op
     p(99.9000) =     22.118 ms/op
     p(99.9900) =     35.258 ms/op
     p(99.9990) =     36.806 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.856 ±(99.9%) 0.259 ms/op
# Warmup Iteration   2: 5.910 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.524 ±(99.9%) 0.020 ms/op
Iteration   1: 5.271 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   4.997 ms/op
                 existUser·p0.90:   6.513 ms/op
                 existUser·p0.95:   7.422 ms/op
                 existUser·p0.99:   9.847 ms/op
                 existUser·p0.999:  23.963 ms/op
                 existUser·p0.9999: 26.950 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   2: 5.275 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.335 ms/op
                 existUser·p0.50:   5.054 ms/op
                 existUser·p0.90:   6.349 ms/op
                 existUser·p0.95:   7.143 ms/op
                 existUser·p0.99:   10.240 ms/op
                 existUser·p0.999:  14.948 ms/op
                 existUser·p0.9999: 28.899 ms/op
                 existUser·p1.00:   29.655 ms/op

Iteration   3: 5.226 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.290 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.382 ms/op
                 existUser·p0.95:   7.496 ms/op
                 existUser·p0.99:   10.059 ms/op
                 existUser·p0.999:  27.492 ms/op
                 existUser·p0.9999: 31.609 ms/op
                 existUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182547
  mean =      5.257 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 91181 
    [ 5.000,  7.500) = 83000 
    [ 7.500, 10.000) = 6514 
    [10.000, 12.500) = 1275 
    [12.500, 15.000) = 362 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.414 ms/op
     p(95.0000) =      7.348 ms/op
     p(99.0000) =      9.994 ms/op
     p(99.9000) =     15.458 ms/op
     p(99.9900) =     30.638 ms/op
     p(99.9990) =     34.093 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 17.385 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.312 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 6.047 ±(99.9%) 0.025 ms/op
Iteration   1: 6.029 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.191 ms/op
                 getUser·p0.50:   5.669 ms/op
                 getUser·p0.90:   7.643 ms/op
                 getUser·p0.95:   8.667 ms/op
                 getUser·p0.99:   12.173 ms/op
                 getUser·p0.999:  24.900 ms/op
                 getUser·p0.9999: 32.201 ms/op
                 getUser·p1.00:   32.309 ms/op

Iteration   2: 6.186 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.552 ms/op
                 getUser·p0.50:   5.808 ms/op
                 getUser·p0.90:   8.020 ms/op
                 getUser·p0.95:   9.093 ms/op
                 getUser·p0.99:   12.567 ms/op
                 getUser·p0.999:  21.702 ms/op
                 getUser·p0.9999: 28.213 ms/op
                 getUser·p1.00:   28.934 ms/op

Iteration   3: 5.899 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.662 ms/op
                 getUser·p0.50:   5.530 ms/op
                 getUser·p0.90:   7.635 ms/op
                 getUser·p0.95:   8.700 ms/op
                 getUser·p0.99:   10.961 ms/op
                 getUser·p0.999:  28.493 ms/op
                 getUser·p0.9999: 31.856 ms/op
                 getUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 159046
  mean =      6.036 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 35073 
    [ 5.000,  7.500) = 104657 
    [ 7.500, 10.000) = 15584 
    [10.000, 12.500) = 2462 
    [12.500, 15.000) = 775 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.191 ms/op
     p(50.0000) =      5.661 ms/op
     p(90.0000) =      7.774 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     11.878 ms/op
     p(99.9000) =     23.755 ms/op
     p(99.9900) =     31.788 ms/op
     p(99.9990) =     32.536 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 18.969 ±(99.9%) 0.313 ms/op
# Warmup Iteration   2: 7.115 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 7.045 ±(99.9%) 0.030 ms/op
Iteration   1: 6.923 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.843 ms/op
                 listUser·p0.50:   6.472 ms/op
                 listUser·p0.90:   8.405 ms/op
                 listUser·p0.95:   10.060 ms/op
                 listUser·p0.99:   15.041 ms/op
                 listUser·p0.999:  28.698 ms/op
                 listUser·p0.9999: 32.531 ms/op
                 listUser·p1.00:   32.768 ms/op

Iteration   2: 6.807 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   3.178 ms/op
                 listUser·p0.50:   6.390 ms/op
                 listUser·p0.90:   8.143 ms/op
                 listUser·p0.95:   9.930 ms/op
                 listUser·p0.99:   13.766 ms/op
                 listUser·p0.999:  31.785 ms/op
                 listUser·p0.9999: 45.848 ms/op
                 listUser·p1.00:   47.448 ms/op

Iteration   3: 6.656 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   6.267 ms/op
                 listUser·p0.90:   8.176 ms/op
                 listUser·p0.95:   9.732 ms/op
                 listUser·p0.99:   13.173 ms/op
                 listUser·p0.999:  25.323 ms/op
                 listUser·p0.9999: 29.686 ms/op
                 listUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141358
  mean =      6.794 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2652 
    [ 5.000, 10.000) = 131928 
    [10.000, 15.000) = 5732 
    [15.000, 20.000) = 699 
    [20.000, 25.000) = 106 
    [25.000, 30.000) = 146 
    [30.000, 35.000) = 63 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      6.373 ms/op
     p(90.0000) =      8.249 ms/op
     p(95.0000) =      9.912 ms/op
     p(99.0000) =     14.074 ms/op
     p(99.9000) =     28.890 ms/op
     p(99.9900) =     44.425 ms/op
     p(99.9990) =     47.204 ms/op
     p(99.9999) =     47.448 ms/op
    p(100.0000) =     47.448 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.494 ± 8.692  ops/ms
ClientPb.existUser                       thrpt       3   5.949 ± 2.790  ops/ms
ClientPb.getUser                         thrpt       3   5.691 ± 1.472  ops/ms
ClientPb.listUser                        thrpt       3   4.763 ± 0.819  ops/ms
ClientPb.createUser                       avgt       3   5.608 ± 2.578   ms/op
ClientPb.existUser                        avgt       3   5.329 ± 1.362   ms/op
ClientPb.getUser                          avgt       3   5.669 ± 3.842   ms/op
ClientPb.listUser                         avgt       3   6.194 ± 0.273   ms/op
ClientPb.createUser                     sample  171778   5.586 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.671           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.963           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.963           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.928           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.118           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.258           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.076           ms/op
ClientPb.existUser                      sample  182547   5.257 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.606           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.005           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.414           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.348           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.994           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.458           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.638           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.472           ms/op
ClientPb.getUser                        sample  159046   6.036 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.191           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.661           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.774           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.847           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.878           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.755           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.788           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.768           ms/op
ClientPb.listUser                       sample  141358   6.794 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.245           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.373           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.249           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.912           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.074           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.890           ms/op
ClientPb.listUser:listUser·p0.9999      sample          44.425           ms/op
ClientPb.listUser:listUser·p1.00        sample          47.448           ms/op
