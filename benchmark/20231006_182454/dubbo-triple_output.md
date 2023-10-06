# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.701 ops/ms
# Warmup Iteration   2: 4.044 ops/ms
# Warmup Iteration   3: 7.453 ops/ms
Iteration   1: 7.335 ops/ms
Iteration   2: 7.784 ops/ms
Iteration   3: 7.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.686 ±(99.9%) 5.720 ops/ms [Average]
  (min, avg, max) = (7.335, 7.686, 7.939), stdev = 0.314
  CI (99.9%): [1.966, 13.406] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.355 ops/ms
# Warmup Iteration   2: 7.296 ops/ms
# Warmup Iteration   3: 8.269 ops/ms
Iteration   1: 8.262 ops/ms
Iteration   2: 8.098 ops/ms
Iteration   3: 8.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.155 ±(99.9%) 1.685 ops/ms [Average]
  (min, avg, max) = (8.098, 8.155, 8.262), stdev = 0.092
  CI (99.9%): [6.470, 9.840] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.081 ops/ms
# Warmup Iteration   2: 6.159 ops/ms
# Warmup Iteration   3: 7.330 ops/ms
Iteration   1: 7.808 ops/ms
Iteration   2: 7.687 ops/ms
Iteration   3: 7.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.741 ±(99.9%) 1.125 ops/ms [Average]
  (min, avg, max) = (7.687, 7.741, 7.808), stdev = 0.062
  CI (99.9%): [6.616, 8.866] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.075 ops/ms
# Warmup Iteration   2: 5.793 ops/ms
# Warmup Iteration   3: 6.463 ops/ms
Iteration   1: 6.500 ops/ms
Iteration   2: 6.477 ops/ms
Iteration   3: 6.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.547 ±(99.9%) 1.868 ops/ms [Average]
  (min, avg, max) = (6.477, 6.547, 6.665), stdev = 0.102
  CI (99.9%): [4.679, 8.416] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.605 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.836 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.338 ±(99.9%) 0.004 ms/op
Iteration   1: 4.147 ±(99.9%) 0.004 ms/op
Iteration   2: 3.989 ±(99.9%) 0.011 ms/op
Iteration   3: 4.106 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.081 ±(99.9%) 1.490 ms/op [Average]
  (min, avg, max) = (3.989, 4.081, 4.147), stdev = 0.082
  CI (99.9%): [2.591, 5.571] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.211 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.559 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.004 ms/op
Iteration   1: 3.907 ±(99.9%) 0.004 ms/op
Iteration   2: 3.959 ±(99.9%) 0.007 ms/op
Iteration   3: 3.822 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.896 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (3.822, 3.896, 3.959), stdev = 0.069
  CI (99.9%): [2.639, 5.153] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.725 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.302 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.117 ±(99.9%) 0.006 ms/op
Iteration   1: 4.196 ±(99.9%) 0.006 ms/op
Iteration   2: 4.131 ±(99.9%) 0.004 ms/op
Iteration   3: 4.083 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.137 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (4.083, 4.137, 4.196), stdev = 0.057
  CI (99.9%): [3.098, 5.175] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.917 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.148 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.062 ±(99.9%) 0.005 ms/op
Iteration   1: 4.953 ±(99.9%) 0.008 ms/op
Iteration   2: 4.709 ±(99.9%) 0.011 ms/op
Iteration   3: 4.934 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.866 ±(99.9%) 2.483 ms/op [Average]
  (min, avg, max) = (4.709, 4.866, 4.953), stdev = 0.136
  CI (99.9%): [2.383, 7.348] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.187 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.817 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.464 ±(99.9%) 0.019 ms/op
Iteration   1: 4.088 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   8.007 ms/op
                 createUser·p0.999:  24.248 ms/op
                 createUser·p0.9999: 28.055 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   2: 4.101 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.581 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   8.069 ms/op
                 createUser·p0.999:  24.576 ms/op
                 createUser·p0.9999: 27.171 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   3: 4.103 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.503 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  27.660 ms/op
                 createUser·p0.9999: 32.145 ms/op
                 createUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234260
  mean =      4.098 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 470 
    [ 2.500,  5.000) = 219710 
    [ 5.000,  7.500) = 10416 
    [ 7.500, 10.000) = 2631 
    [10.000, 12.500) = 420 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      8.253 ms/op
     p(99.9000) =     24.764 ms/op
     p(99.9900) =     30.671 ms/op
     p(99.9990) =     32.396 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.303 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 4.531 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.182 ±(99.9%) 0.014 ms/op
Iteration   1: 3.884 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.651 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   8.151 ms/op
                 existUser·p0.999:  11.654 ms/op
                 existUser·p0.9999: 26.010 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   2: 3.983 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.401 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   8.487 ms/op
                 existUser·p0.999:  22.271 ms/op
                 existUser·p0.9999: 69.861 ms/op
                 existUser·p1.00:   71.827 ms/op

Iteration   3: 3.880 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   7.438 ms/op
                 existUser·p0.999:  27.574 ms/op
                 existUser·p0.9999: 30.744 ms/op
                 existUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245108
  mean =      3.915 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 231921 
    [ 5.000, 10.000) = 12226 
    [10.000, 15.000) = 671 
    [15.000, 20.000) = 38 
    [20.000, 25.000) = 67 
    [25.000, 30.000) = 131 
    [30.000, 35.000) = 22 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 25 
    [70.000, 75.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      8.053 ms/op
     p(99.9000) =     21.816 ms/op
     p(99.9900) =     69.337 ms/op
     p(99.9990) =     71.696 ms/op
     p(99.9999) =     71.827 ms/op
    p(100.0000) =     71.827 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.468 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 4.808 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.192 ±(99.9%) 0.014 ms/op
Iteration   1: 4.319 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.776 ms/op
                 getUser·p0.50:   4.116 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   6.226 ms/op
                 getUser·p0.99:   8.880 ms/op
                 getUser·p0.999:  20.251 ms/op
                 getUser·p0.9999: 26.758 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   2: 4.136 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.292 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   8.447 ms/op
                 getUser·p0.999:  26.039 ms/op
                 getUser·p0.9999: 40.471 ms/op
                 getUser·p1.00:   40.960 ms/op

Iteration   3: 4.053 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.679 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   8.142 ms/op
                 getUser·p0.999:  15.876 ms/op
                 getUser·p0.9999: 29.633 ms/op
                 getUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 230343
  mean =      4.166 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 216124 
    [ 5.000, 10.000) = 13156 
    [10.000, 15.000) = 745 
    [15.000, 20.000) = 49 
    [20.000, 25.000) = 57 
    [25.000, 30.000) = 179 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     24.586 ms/op
     p(99.9900) =     37.091 ms/op
     p(99.9990) =     40.875 ms/op
     p(99.9999) =     40.960 ms/op
    p(100.0000) =     40.960 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.384 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 5.461 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.937 ±(99.9%) 0.018 ms/op
Iteration   1: 4.846 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.944 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.267 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  26.608 ms/op
                 listUser·p0.9999: 30.926 ms/op
                 listUser·p1.00:   31.556 ms/op

Iteration   2: 4.870 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   9.060 ms/op
                 listUser·p0.999:  19.235 ms/op
                 listUser·p0.9999: 25.489 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   3: 4.881 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.064 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  16.433 ms/op
                 listUser·p0.9999: 21.686 ms/op
                 listUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197198
  mean =      4.866 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 153741 
    [ 5.000,  7.500) = 36999 
    [ 7.500, 10.000) = 4767 
    [10.000, 12.500) = 920 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 246 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.597 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      6.103 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     19.556 ms/op
     p(99.9900) =     30.507 ms/op
     p(99.9990) =     31.460 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.686 ± 5.720  ops/ms
ClientPb.existUser                       thrpt       3   8.155 ± 1.685  ops/ms
ClientPb.getUser                         thrpt       3   7.741 ± 1.125  ops/ms
ClientPb.listUser                        thrpt       3   6.547 ± 1.868  ops/ms
ClientPb.createUser                       avgt       3   4.081 ± 1.490   ms/op
ClientPb.existUser                        avgt       3   3.896 ± 1.257   ms/op
ClientPb.getUser                          avgt       3   4.137 ± 1.039   ms/op
ClientPb.listUser                         avgt       3   4.866 ± 2.483   ms/op
ClientPb.createUser                     sample  234260   4.098 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.014           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.653           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.253           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.764           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.671           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.506           ms/op
ClientPb.existUser                      sample  245108   3.915 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.760           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.053           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.816           ms/op
ClientPb.existUser:existUser·p0.9999    sample          69.337           ms/op
ClientPb.existUser:existUser·p1.00      sample          71.827           ms/op
ClientPb.getUser                        sample  230343   4.166 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.292           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.653           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.300           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.585           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.586           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.091           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.960           ms/op
ClientPb.listUser                       sample  197198   4.866 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.597           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.103           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.421           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.556           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.507           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.556           ms/op
